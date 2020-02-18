<template>
  <div id="app">
     <b-row>
     <b-col class="b1" cols="1" ></b-col>
     <b-col class="b2" cols="5">
    <Faqs />

     </b-col>
     <b-col class="b3" cols="6">
       <br>
       <TroubleShoting />
     </b-col>
   </b-row>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Faqs from './components/FAQS.vue'
import  TroubleShoting  from "./components/TroubleShoting.vue";
export default {
  name: 'App',
  components:{
    Faqs,
    TroubleShoting
  }
}
</script>

<style>
#app{
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    height:100vh;
}
</style>
