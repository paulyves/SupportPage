<template>
  <div class="footer">
      <footer class="site-footer">
          <nav class="site-nav">
              <div class="menu-footer-container">
                  <ul id="menu-footer" class="menu">
                      <li id="menu-item-53" class=" menu-item-53">
                          <a href="http://wavephonehome.com/#about">About</a>
                      </li>
                      <li id="menu-item-54" class=" menu-item-54">
                          <a href="http://wavephonehome.com/#specification">Specification</a>
                      </li>
                      <li id="menu-item-43" class=" menu-item-41">
                          <a href="http://wavephonehome.com/resources/">Resources</a>
                      </li>
                      <li id="menu-item-56" class=" menu-item-56">
                          <a href="http://wavephonehome.com/#contact">Contact US</a>
                      </li>
                  </ul>
              </div>
          </nav>
          <a href="">
              <img src="@/assets/wavephonewhitelogo.png" alt="wavephone-logo" id="wavephone-logo">
          </a>
          <div class="footer-desc">
              <p>
                  A versatile landline service the whole family can get behind,
                  <br/>
                  that makes reaching your loved ones easier than ever.
                  <br/>
                  A proud innovation from Bluewave Global.
              </p>
          </div>
      </footer>

  </div>
</template>

<script>
export default {
name:'footer'
}
</script>

<style scoped>
footer{
    display: block;
    
}
.site-footer{
    text-align:center;
    width: 100%;
    background-color: #313131;
    padding:100px;
}
.site-footer .site-nav{
    display: inline-block;
    width:100%;
}
.site-footer .site-nav ul{
    margin-bottom: 0;
}
ul{
    margin-top:0;
}
.site-footer .site-nav ul li{
    list-style: none;
    display: inline-block;
}
.site-footer .site-nav ul li a{
    margin-left: 20px;
    margin-right:20px;
    text-transform: uppercase;
    text-decoration: none;
    color: #ffffff;
    font-size: 14px;
}
.site-footer .site-nav ul li a:hover{
    color:#428bca;
}
img{
    height: auto;
    overflow: hidden;
    vertical-align: middle;
    border:0;
}
.site-footer #wavephone-logo{
    width:160px;
    margin: 50px 0;
}
.site-footer .footer-desc p{
    color: #737373;

}
p{
    margin: 0 0 10px;
    font-size: 14px;
}
@media screen and (max-width: 600px) {
  ul#menu-footer {
    display: block;
    padding:0px !important;
  }
}

</style>