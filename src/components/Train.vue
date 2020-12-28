<template>
  <div class="Train">
    输入<input type="text" v-model="msg" />
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'Train',
  props: {
    
  },data(){
    return{
      msg:''
    }
  }
}
</script>

<style scoped>

</style>
