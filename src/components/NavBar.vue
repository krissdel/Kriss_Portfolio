<template>
  <div id="nav_bar">
    <!-- <a class="logo" rel="index" href="#"> -->

    <!-- </a> -->
    <nav class="nav_bar_icons">
      <router-link to="/">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-home"></i>
        </span>
      </router-link>

      <router-link to="/about">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-user"></i>
        </span>
      </router-link>

      <span style="font-size: 1.5em; color: white">
        <i class="fas fa-eye"></i>
      </span>

      <router-link to="/projects">
        <span style="font-size: 1.5em; color: white">
          <i class="fas fa-briefcase"></i>
        </span>
      </router-link>

      <router-link to="/contact"
        ><span style="font-size: 1.5em; color: white">
          <i class="fas fa-envelope"></i> </span
      ></router-link>
    </nav>
    <!-- <ul></ul> -->
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style>
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
}
</style>