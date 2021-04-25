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
  //  data() {
  //       return {
  //           words: [
  //               { text: 'Vue', value: 1000 },
  //               { text: 'js', value: 200 },
  //               { text: 'is', value: 800 },
  //               { text: 'very cool', value: 1000000 },
  //               { text: 'lunch', value: 100 },
  //           ],
  //           fontSizeMapper: word => Math.log2(word.value) * 5,
  //       }
  //   },
  components: {
    SoftSkills,
    // Cloud,
  }
}
</script>
