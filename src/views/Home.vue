<template>
  <div class="home">
   <!-- <Cloud />  -->
  <SoftSkills msg="Christian DELORME "/>
   <!-- <cloud :data="words" :fontSizeMapper="fontSizeMapper" /> -->
  </div>
</template>

<script>
// @ is an alias to /src

import SoftSkills from '@/components/SoftSkills.vue'
// import Cloud from '@/components/Cloud.vue'

export default {
  name: 'home',
  components: {
    SoftSkills,
    // Cloud,
  }
}
</script>
