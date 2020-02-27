<template>
  <div class="main-support">
    <Navbar />
      <div class="container">
      <FAQS />
        <Troubleshoting />
      </div>
      
      <Footer />
  </div>
</template>

<script>
import FAQS from './FAQS.vue'
import Troubleshoting from './TroubleShoting.vue'
import Footer from './Footer.vue'
import Navbar from './Navbar.vue'
export default {
name: 'main-support',
components:{
  Troubleshoting,
    FAQS,
    Footer,
    Navbar
}
}
</script>

<style scoped>
.container{
  padding-bottom: 100px;
  padding-top:300px;
}
.qa-class {
  color: #3b6da8;
  font-weight: bold;
  /* margin-left: 10%;
  margin-right:10%; */
}
</style>