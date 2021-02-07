<template>
  <h1>My Projects</h1>

  <!-- <div class="container">
    <div class="container">
      <div class="row row-cols-2">
        <div class="col">
          <div class="projects_image">
            <img src="../assets/groupomania_projet.png" />
          </div>
        </div>
        <div class="col">
          <div class="projects_image">
            <img src="../assets/so_pekocko.png" />
          </div>
        </div>
        <div class="col">
          <div class="projects_image">
            <img src="../assets/chouette_agence.png" />
          </div>
        </div>
        <div class="col">
          <div class="projects_image">
            <img src="../assets/orinoco.png">
          </div>
        </div>

        <div class="col">
          <div class="projects_image">
            <img src="../assets/ohmyfood.png">
          </div>
        </div>
        <div class="col">
          <div class="projects_image">
            <img src="../assets/cv.png">
          </div>
        </div>
      </div>
    </div>
  </div> -->

 
<div class="grid-container">
    
    <div class="projects_image"><img src="../assets/groupomania_projet.png"></div>
    
    <div class="projects_image"><img src="../assets/so_pekocko.png"></div>
    
    <div class="projects_image"><img src="../assets/orinoco.png"></div>
    
    <div class="projects_image"><img src="../assets/chouette_agence.png"></div>
    
    <div class="projects_image"><img src="../assets/ohmyfood.png"></div>
    
    <div class="projects_image"><img src="../assets/cv.png"></div>

</div>
</template>

<script>
export default {
  name: "projects",
  components: {
      
  },
};
</script>

<style>
img {
  width: 100%;
  height: auto;
}

.grid-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  grid-gap: 1em;
}
</style>