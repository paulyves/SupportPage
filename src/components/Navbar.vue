<template>
  <div class="nav-section">
    <header
      class="site-header"
      style="position: fixed; left: 0px; top: 0px; width: 100%; margin-left: 0px; padding: 0px; margin-top: 0px; z-index: 1;"
    >
      <div class="navbar ">
        <a href="http://wavephonehome.com"
          ><img
            id="wavephone-logo"
            src="@/assets/wavephonebluelogo.png"
        /></a>
        <a
          href="javascript:void(0);"
          class="icon mt-3"
          @click.prevent="navFunction"
        >
          <i class="material-icons">
            menu
          </i>
        </a>
        <nav class="site-nav" id="mySite-nav">
          <a href=""></a>
          <a
            class="mega-menu-link"
            href="http://wavephonehome.com/#about"
            tabindex="0"
            >About</a
          >
          <a
            class="mega-menu-link"
            href="http://wavephonehome.com/#specification"
            tabindex="0"
            >Specifications</a
          >
          <a
            class="mega-menu-link"
            href="http://wavephonehome.com/resources/"
            tabindex="0"
            >Resources</a
          >
          <a
            class="mega-menu-link"
            href="http://wavephonehome.com/#contact"
            tabindex="0"
            >Contact Us</a
          >

          <!-- </div> -->

          <!-- <div id="mega-menu-wrap-header" class="mega-menu-wrap">
    <ul>
        <li class="mega-menu-item"><a class="mega-menu-link" href="http://wavephonehome.com/#about" tabindex="0">About</a></li>
        <li class="mega-menu-item"><a class="mega-menu-link" href="http://wavephonehome.com/#specification" tabindex="0">Specifications</a></li>
        <li class="mega-menu-item"><a class="mega-menu-link" href="http://wavephonehome.com/resources/" tabindex="0">Resources</a></li>
        <li class="mega-menu-item"><a class="mega-menu-link" href="http://wavephonehome.com/#contact" tabindex="0">Contact Us</a></li>
    </ul>
    
</div> -->
        </nav>
      </div>
      <div class="black-space">
        <div class="breadcrumbs">
          <a href="http://wavephonehome.com">Home</a><span> &gt; </span>
          <a href="http://wavephonehome.com/resources">Resources</a
          ><span> &gt; </span>
          <a href="http://wavephonehome.com">FAQs and Trouble shooting</a>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "navbar",

  methods: {
    navFunction() {
      let nav = document.getElementById("mySite-nav");
      if (nav.className === "site-nav") {
        nav.className += " responsive";
      } else {
        nav.className = "site-nav";
      }
    }
  }
};
</script>
<style scoped>
.site-nav {
  overflow: hidden;
  background-color: #fff;
}
.site-nav a {
  float: left;
  display: block;
  color: #333333;
  text-align: center;
  padding: 0px 14px;
  text-decoration: none;
  font-size: 14px;
  text-transform: uppercase;
  transition: 0.5s ease-out;
}
.icon {
  display: none;
}
.material-icons {
  color: #218cc2;
  font-size: 30px;
}
@media screen and (max-width: 600px) {
  .site-nav a:not(:first-child) {
    display: none;
  }
  a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .site-nav.responsive {
    position: relative;
  }
  .site-nav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .site-nav.responsive a {
    float: none;
    display: block;
    text-align: left;
    padding: 10px;
  }
}
/* pause */
.site-header .site-nav {
  margin-top: 30px;
}
.navbar {
  min-height: 50px;
  padding: 30px 360px;
  margin-bottom: 20px;
}
.navbar #wavephone-logo {
  display: inline-block;
  width: 160px;
  float: left;
}
.site-header {
  background-color: #ffffff;
  border-bottom: 1px solid #eee;
}
.black-space {
  width: 100%;
  z-index: 999;
  padding: 25px;
  background-color: #313131;
}
.breadcrumbs {
  text-align: right;
  color: #fff;
  margin-right: 350px;
}
.breadcrumbs a {
  text-decoration: none;
  color: #fff;
  font-size: 14px;
  background: 0 0;
  display: inline-block;
}
.navbar .site-nav {
  display: inline-block;
  float: right;
}

@media (max-width: 425px) {
  .navbar {
    margin-bottom: 0 !important;
  }
  .menu-icon {
    display: block;
  }
  .site-nav {
    margin-top: 0px !important;
    width: 100%;
  }
}
@media (max-width: 768px) {
  .navbar #wavephone-logo {
    /* display: inline-block; */
    width: 180px !important;
  }
  .navbar {
    padding: 20px 50px 25px 50px;
  }
  .breadcrumbs {
    margin-right: 50px;
  }
}
/* @media (max-width: 1020px) {
  .navbar #wavephone-logo {
    display: inline-block;
    width: 180px !important;
  }
  .navbar {
    padding: 30px 120px ;
  }
  .breadcrumbs {
    margin-right: 50px;
  }
}
@media  (max-width: 1440px){
 
} */

</style>
