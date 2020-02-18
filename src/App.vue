<template>
  <div id="app">
    <Faqs />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Faqs from './components/FAQS.vue'
export default {
  name: 'App',
  components:{
    Faqs
  }
}
</script>

<style>
#app{
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    height:100vh;
}
</style>
