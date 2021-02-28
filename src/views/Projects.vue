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

  <!-- ================================= -->
  <div class="grid-container">
    <div class="child-page-listing">
      <h2>projects</h2>

      <article class="">
        <a class="" href="#">R'extense</a>
        <div class="">
          <a href="#"> <img src="../assets/rextense.png" /> </a>
        </div>
      </article>

      <article class="">
        <a class="" href="#">Groupomania</a>
        <div class="">
          <a href="#">
            <img src="../assets/groupomania_projet2.png" />
          </a>
        </div>
      </article>

      <article class="">
        <a class="" href="#">So pekocko</a>
        <div class="">
          <a href="#">
            <img src="../assets/so_pekocko2.png" />
          </a>
        </div>
      </article>

      <article class="">
        <a class="" href="#">Orinoco</a>
        <div class="">
          <a href="#">
            <img src="../assets/orinoco2.png" />
          </a>
        </div>
      </article>
      <article class="">
        <a class="" href="#">La Chouette Agence</a>
        <div class="">
          <a href="#">
            <img src="../assets/chouette_agence2.png" />
          </a>
        </div>
      </article>

      <article class="">
        <a class="" href="#">Ohmyfood</a>
        <div class="">
          <a href="#"> <img src="../assets/ohmyfood2.png" /> </a>
        </div>
      </article>

      <article class="">
        <a class="" href="#">CV</a>
        <div class="">
          <a href="#"> <img src="../assets/cv2.png" /> </a>
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
export default {
  name: "projects",
  components: {},
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