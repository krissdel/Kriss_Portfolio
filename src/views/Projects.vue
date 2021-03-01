<template>
  <h1>My Projects</h1>

  <Loader />


  <!-- ================================= -->
  <div class="grid-container">
    <div class="child-page-listing">
      <h2>projects</h2>

      <article class="project-listing">
        <a class="project-link" href="https://github.com/krissdel/Rextense" target="_blank">Lien Github</a>
        <div class="project-image">
          <a href="https://rextense.com/" target="_blank"><img src="../assets/rextense.png" alt="image rextense "/> </a>
        </div>
      </article>

      <article class="project-listing">
        <a class="project-link" href="https://github.com/krissdel/groupomania">Lien Github</a>
        <div class="project-image">
          <a href="#">
            <img src="../assets/groupomania_projet2.png" alt="image groupomania"/>
          </a>
        </div>
      </article>

      <article class="project-listing">
        <a class="project-link" href="#">Lien Github</a>
        <div class="project-image">
          <a href="#">
            <img src="../assets/so_pekocko2.png" alt="image so_pekocko"/>
          </a>
        </div>
      </article>

      <article class="project-listing">
        <a class="project-link" href="#">Lien Github</a>
        <div class="project-image">
          <a href="#">
            <img src="../assets/orinoco2.png" alt="image orinoco"/>
          </a>
        </div>
      </article>
      <article class="project-listing">
        <a class="project-link" href="#">Lien Github</a>
        <div class="project-image">
          <a href="#">
            <img src="../assets/chouette_agence2.png" alt="image la chouette agence"/>
          </a>
        </div>
      </article>

      <article class="project-listing">
        <a class="project-link" href="#">Lien Github</a>
        <div class="project-image">
          <a href="#"> <img src="../assets/ohmyfood2.png" alt="image ohmyfood"/> </a>
        </div>
      </article>

      <article class="project-listing">
        <a class="project-link" href="#">Lien Github</a>
        <div class="project-image">
          <a href="#"> <img src="../assets/cv2.png" alt="image projet CV"/> </a>
        </div>
      </article>
    </div>

    <!-- ======================= -->

    <!-- <div class="projects_image">
      <img src="../assets/groupomania_projet.png" />
    </div>

    <div class="projects_image"><img src="../assets/so_pekocko.png" /></div>

    <div class="projects_image"><img src="../assets/orinoco.png" /></div>

    <div class="projects_image">
      <img src="../assets/chouette_agence.png" />
    </div>

    <div class="projects_image"><img src="../assets/ohmyfood.png" /></div>

    <div class="projects_image"><img src="../assets/cv.png" /></div>
  </div> -->
  </div>
</template>

<script>
import Loader from '@/components/Loader.vue'


export default {
  name: "projects",
  components: {
    Loader
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
  margin-left: 10pc;
}
</style>