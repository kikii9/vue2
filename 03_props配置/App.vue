<template>
  <div id="app">
    
    <Student :name='name' age="20"></Student>
</div>
</template>

<script>
import Student from '@/components/Student'

export default {
  name: 'App',
  data(){
    return{ 
      name:'tom'
    }
  },
  components: {
   Student,
  },
 
}
</script>

<style>

</style>
