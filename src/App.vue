<template>
  <div id="app">
    <b-container id="containerId" class="containerStyle pl-sm-5 pl-md-0  pl-0 mt-md-0  mt-3 ">

     <b-row>
 
     <b-col class="b2 " md="6">
    <Faqs />

     </b-col>
     <b-col class="b3 " md="6">
      
       <TroubleShoting />
     </b-col>
   </b-row>
    </b-container>
  </div>
</template>

<script>

import Faqs from './components/FAQS.vue'
import  TroubleShoting  from "./components/TroubleShoting.vue";
export default {
  name: 'App',
  components:{
    Faqs,
    TroubleShoting
  },

  data(){
    return {
   
    }
  },

  methods:{
  
  },

  watch:{
    
  }
}
</script>

<style scoped>
#app{
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    height:100vh;
}

.containerStyle{
  /* border: solid green 2px; */
  /* width: 80%; */
  max-width: 80%;



   /* display: grid;  
    grid-gap: 5px;  
    /* grid-template-columns: repeat(auto-fit, 100px); */
    /* grid-template-rows: repeat(2, 100px);    */
}

.b3{
  margin-top: 7.2%;
}

.b2{
  margin-top: 2%;
}

.containerStyle1{
   max-width: 95%;
   background-color: yellow;
}

</style>
