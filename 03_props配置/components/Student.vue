<template>
  <div>
    {{name}}
    {{age}}
  </div>
</template>

<script>
export default {
    data(){
        return{

        }
    },
    // props子组件配置接收
    props:['name','age']
}
</script>

<style>

</style>