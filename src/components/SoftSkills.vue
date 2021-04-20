<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <div class="tags">
      <span class="tags1"> 𓀾 𓀿 𓁀 𓁁 𓁂 𓁃 𓁄 𓁅 </span>
      <span class="tags2"> 𓁆 𓁇 𓁈 𓁉 𓁍 𓁎 𓁏 </span>
      
    </div>
    
        <!-- <router-link to="/Projects"> -->
<!-- <button type="button" class="btn btn-white btn- animate">projects</button> -->
<div class="text-box">
      <a href="#" class="btn btn-white btn- animate"> soft</a>
    </div>

          <span class="tags5"> 𓁆 𓁇 𓁈 𓁉 𓁍 𓁎 𓁏 </span>

    <!-- </router-link>  -->

    <div>
            <span class="tags4"> 𓁆 𓁇 𓁈 𓁉 𓁍 𓁎 𓁏 </span>

      <ul>
        <li><a href="#">Mot clé 1</a></li>
        <li><a href="#">Mot clé 2</a></li>
        <li><a href="#">Mot clé 3</a></li>
        <li><a href="#">Mot clé 4</a></li>
        <li><a href="#">Mot clé 5</a></li>
        <li><a href="#">Mot clé 6</a></li>
        <li><a href="#">Mot clé 7</a></li>
        <li><a href="#">Mot clé 8</a></li>
        <li><a href="#">Mot clé 9</a></li>
        <li><a href="#">Mot clé 10</a></li>
        <li><a href="#">Mot clé 11</a></li>
        <li><a href="#">Mot clé 12</a></li>
        <li><a href="#">Mot clé 13</a></li>
        <li><a href="#">Mot clé 14</a></li>
        <li><a href="#">Mot clé 15</a></li>
        <li><a href="#">Mot clé 16</a></li>
        <li><a href="#">Mot clé 17</a></li>
        <li><a href="#">Mot clé 19</a></li>
      </ul>
    </div>
  </div>
        <span class="tags6"> 𓁆 𓁇 𓁈 𓁉 𓁍 𓁎 𓁏 </span>

</template>

<script>

export default {
  name: "Home",
  props: {
    msg: String,
  },


  mounted () {
},

  methods: {
 
  
}
}
</script>


<style lang="css" scoped>


h1 {
  font-family: "Libre Baskerville", serif;
  color: white;
}
.tags1 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
  bottom: auto;
  top: 0;
  display: flex;
  color: #515152;
}
.tags2 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
  bottom: 50px;
  top: 0;
  display: flex;
  justify-content: flex-end;
  color: #515152;
}
/* .tags3 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
  top: 0;
  color: #515152;
   margin-left: -29vw;
  margin-top: 21vh;
} */
.tags4 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
display: flex;
  top: 0;
  color: #515152;
   margin-left: 18vw;
  margin-top: 21vh;
}
.tags5 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
  bottom: 50px;
  top: 0;
  display: flex;
  color: #515152;
   margin-left: 66vw;
  margin-top: 21vh;
}
.tags6 {
  font-size: 20px;
  font-family: "La Belle Aurore", cursive;
  bottom: 50px;
  top: 0;
  display: flex;
  color: #515152;
   margin-left: 80vw;
  margin-top: 21vh;
}

/* -----[button soft skills]--------------- */

a.btn.btn-white.btn-.animate {
  font-family: "Libre Baskerville", serif;
  border-color: rgb(17, 236, 229);;
  /* background: rgb(17, 236, 229); */
  box-shadow: rgb(17 236 229) 0px 0px 6px 0.7px
}
/* body {
  background-color: #060b0e;
  font-weight: bold;
  width: 900px;
} */

.text-box {
  margin-left: -11vw;
  margin-top: 21vh;
}

.btn:link,
.btn:visited {
  text-transform: uppercase;
  text-decoration: none;
  padding: 15px 40px;
  display: inline-block;
  border-radius: 100px;
  transition: all 0.2s;
  position: absolute;
}

.btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.btn:active {
  transform: translateY(-1px);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

.btn-white {
  background-color: #ffffff;
  color: #777;
}

.btn::after {
  content: "";
  display: inline-block;
  height: 100%;
  width: 100%;
  border-radius: 100px;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
  transition: all 0.4s;
}

.btn-white::after {
  background-color: #fff;
}

.btn:hover::after {
  transform: scaleX(1.4) scaleY(1.6);
  opacity: 0;
}

.btn-animated {
  animation: moveInBottom 5s ease-out;
  animation-fill-mode: backwards;
}

@keyframes moveInBottom {
  0% {
    opacity: 0;
    transform: translateY(30px);
  }

  100% {
    opacity: 1;
    transform: translateY(0px);
  }
}

/* -----[keyword cloud]------------------------- */

#tagsphere{
  background: url('/images/background.png') top center no-repeat;
  height: 230px; width: 380px;
  padding: 10px;
  margin: 10px;
  margin: 0 auto;
}
ul li a, ul li a:visited{
  color: #E29154;
  font-weight: bold;
  text-decoration: none;
}
ul li a:hover, ul li.link1 a:hover, ul li.link2 a:hover, ul li.link3 a:hover{
  color: #4EB6BF;
}
ul li.link1 a{
  color: #D8B596;
}
ul li.link2 a{
  color: #EAAF84
}
ul li.link3 a{
  color: #FF8000;
}
</style>
