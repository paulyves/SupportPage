<template>
<div class="navbar">
    <!-- <b-navbar>
        <b-navbar-brand href="#">Bluewave Global</b-navbar-brand>
    </b-navbar> -->
     <b-navbar class="backColor" toggleable="lg" type="dark" >
          <b-navbar-brand href="#"><h2>Bluewave Global</h2></b-navbar-brand>

          <!-- <b-navbar-nav >
              <b-nav-item right>

              <b-nav-form right>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
              </b-nav-form>
              </b-nav-item>
          </b-navbar-nav> -->

     </b-navbar>
    <!-- <h1>hello</h1> -->
</div>
</template>

<script>
export default {
    name: "navbar",

}
</script>
<style scoped>

.navbar{
    background-color: #2aabdf;
        padding-left: 0px;
    padding-right: 0px;
    padding-top: 0px;
    height:10vh;
}
.backColor{
    /* background-color: #2aabdf; */
    margin-left: 10px;
}

.navbar-brand{
        padding-top: 40px;
}
</style>