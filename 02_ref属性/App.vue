<template>
  <div id="app">
    <h1 v-text="msg" ref="title"></h1>
    <button  ref="btn" @click="show">ref属性 获取dom元素</button>
    <School ref="sch"></School>
  </div>
</template>

<script>
import School from '@/components/School'

export default {
  name: 'App',
  data(){
    return{ 
      msg:'hello'
    }
  },
  components: {
   School,
  },
  methods:{
    show(){
      console.log('@')
      console.log(this.$refs);
      console.log(this.$refs.title);
      console.log(this.$refs.sch);
      console.log(this.$refs.btn);
    }
  }
}
</script>

<style>

</style>
