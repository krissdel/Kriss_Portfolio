<template>
<!-- <div class="card"> -->

  <h1>Contact</h1>
<!-- <div class="container">  -->
  <div class="container">
    <div class="row">
      <div class="col">
        <input
          type="text"
          class="form-control"
          placeholder="First name"
          aria-label="First name"
        />
      </div>
      <div class="col">
        <input
          type="text"
          class="form-control"
          placeholder="Last name"
          aria-label="Last name"
        />
      </div>
      <div class="col">
        <label for="inputEmail4" class="form-label"></label>
        <input
          type="email"
          class="form-control"
          id="inputEmail4"
          placeholder="Email"
        />
      </div>
      <div class="col">
        <textarea
          class="form-control"
          placeholder="Leave a message here"
          id="floatingTextarea2"
          style="height: 100px"
        ></textarea>
        <!-- <label for="floatingTextarea2">Comments</label> -->
    
      
     
    </div>
    </div>
       <div class="col-btn">
        <input class="btn btn-primary" type="submit" value="Envoyer" />
      </div>
  </div>
  <!-- </div> -->
<!-- </div> -->
</template>

<script>
</script>

<style scoped>
.container {
    max-width: 800px;
    padding-top: 5pc;
    width: fit-content;
}
.col {
  padding-bottom: 5pc;
}
.row {
  flex-direction: column;
}

label {
  display: none;
}
.col-btn {
    padding-top: 4pc;
}

input.btn.btn-primary {
    width: 48pc;
}
.btn-primary {
    color: #fff;
    background-color: #3c4776;
    border-color: #3c4776;
}

</style>>
