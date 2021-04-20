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
#nav_bar {
  background: #181818;
  width: 60px;
  height: 100%;
  position: fixed;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  z-index: 3;
  min-height: 500px;
  padding-block: 12pc;

}
.nav_bar_icons {
  background: #181818;
  width: 60px;
  height: 100%;
  position: fixed;
  top: 0;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  z-index: 3;
  min-height: 500px;
  padding-block: 12pc;
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