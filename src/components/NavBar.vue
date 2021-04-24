<template>
  <div id="nav_bar">
    <nav class="nav_bar_icons">
      <router-link to="/">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-home"></i>
          <!-- <b>Home</b> -->
        </span>
      </router-link>
      <router-link to="/about">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-user"></i>
          <!-- <b>About</b> -->
        </span>
      </router-link>

      <span style="font-size: 1.5em; color: white">
        <i class="fas fa-eye"></i>
        <!-- <b>Skills</b> -->
      </span>

      <router-link to="/projects">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-briefcase"></i>
          <!-- <b>My Projects</b> -->
        </span>
      </router-link>

      <router-link to="/contact"
        ><span style="font-size: 1.5em; color: white">
          <i class="fas fa-envelope"></i>
          <!-- <b>Contact</b>  -->
      </span></router-link>

<div style="top: 0px; left: 100%; width: 2%;" data-v-4295d220="" class="SignupBannerBottom__GlowingLine-sc-1lyynxn-5 gLPqNG"></div>
    
<div data-v-4295d220="" class="SignupBannerBottom__GlowingLine-sc-1lyynxn-5 gLPqNH" style="top: 10pc; left: 100%; width: 2%;"></div>
<div data-v-4295d220="" class="SignupBannerBottom__GlowingLine-sc-1lyynxn-5 gLPqNH" style="top: 35pc; left: 100%; width: 2%;"></div>
<div data-v-4295d220="" class="SignupBannerBottom__GlowingLine-sc-1lyynxn-5 gLPqNI" style="top: 25pc; left: 100%; width: 2%;"></div>
<div data-v-4295d220="" class="SignupBannerBottom__GlowingLine-sc-1lyynxn-5 gLPqNJ" style="top: 45pc; left: 100%; width: 2%;"></div>

</nav>

  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
/* -----[nav bar]--------------------- */
/* ::after {
  box-sizing: border-box; 
  box-sizing: content-box;
} */
* {
  -webkit-box-sizing: content-box;
     -moz-box-sizing: content-box;
          box-sizing: content-box;
}
*:before,
*:after {
  -webkit-box-sizing: content-box;
     -moz-box-sizing: content-box;
          box-sizing: content-box;
}
/* =====[glowing lines]================================== */
.gLPqNG {
    position: absolute;
    height: 63px;
    background: rgb(17, 236, 229);
    box-shadow: rgb(17 236 229) 0px 0px 6px 0.7px;
}
.gLPqNH {
    position: absolute;
    height: 20px;
    background: rgb(17, 236, 229);
    box-shadow: rgb(17 236 229) 0px 0px 6px 0.7px;
}
.gLPqNI {
    position: absolute;
    height: 108px;
    background: rgb(17, 236, 229);
    box-shadow: rgb(17 236 229) 0px 0px 6px 0.7px;
}
.gLPqNJ {
    position: absolute;
    height: 115px;
    background: rgb(17, 236, 229);
    box-shadow: rgb(17 236 229) 0px 0px 6px 0.7px;
}
/* ====================================================== */

#nav_bar {
     background: #181818;
    /* border-color: red; */
    width: 60px;
    height: 100%;
    position: fixed;
    top: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    z-index: 3;
    min-height: 500px;
    border: 1px solid rgb(42 97 95);
}
.nav_bar_icons {
    background: #181818;
    width: 60px;
    height: 100%;
    position: fixed;
    top: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    z-index: 3;
    min-height: 500px;
}

/* =====[icones hover]============================ */
.nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    position: absolute;
    top: 0;
    right: 0;
}
.nav li {
    font-size:12pt;
    display:block;
    float: left;
    height:90px;
    width: 145px; /*new*/
    text-align: center; /*new*/
    transition: all 0.2s ease-in-out;
}
/* .nav .home {
    background: #a3d39c;
}
.nav .about {
    background: #7accc8;
}
.nav .projects {
    background: #4aaaa5;
}
.nav .contact {
    background: #35404f;
} */
.nav li a {
    font-family: FontAwesome;
    color:#eee;
    font-size:22pt;
    text-decoration: none;
    display: block;
    padding:15px;
}
.nav li i {
    color:#fff;
    padding:0 10px;
}
.nav li b {
    padding: 15px 0;
    display: none;
}
.nav a:hover {
    color: #fff;
}
.nav a:hover i {
    display: none;
}
.nav a:hover b {
    display: block;
}
</style>