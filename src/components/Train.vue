<template>
  <div class="Train">
    v-model输入1<input type="text" v-model="str_1" />&nbsp;&nbsp;&nbsp;
    v-model输入2<input type="text" v-model="str_1" />&nbsp;&nbsp;&nbsp;显示{{str_1}}
    <br/>
    v-model.trim&nbsp;<input type="text" v-model.trim="str_2">&nbsp;&nbsp;&nbsp;长度：{{str_2.length}}
    <br/>
    v-model.number:<input type="text" v-model.number="num_1">&nbsp;&nbsp;&nbsp;转换：{{num_1}}
    <br/>
    v-model.lazy:<input type="text" v-model.lazy="num_2">&nbsp;&nbsp;&nbsp;转换：{{num_2}}
  </div>
</template>

<script>
export default {
  name: 'Train',
  props: {
    
  },data(){
    return{
      str_1:'',
      str_2:'',
      num_1:0,
      num_2:0
    }
  },methods:{
  }
}
</script>

<style scoped>

</style>
