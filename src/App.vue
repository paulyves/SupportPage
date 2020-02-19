<template>
  <div id="app">
    <b-container class="containerStyle">

     <b-row>
 
     <b-col class="b2" md="6">
    <Faqs />

     </b-col>
     <b-col class="b3" md="6">
      
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
}

.b3{
  margin-top: 5.4%;
}

</style>
