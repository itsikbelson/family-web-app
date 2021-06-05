<template>
  <v-app id="family-app">
    <nav-bar />
    <nuxt />
  </v-app>
</template>

<script>
import NavBar from '~/components/NavBar.vue'
export default {
  components: {
    NavBar
  }
}
</script>

<!--<script>-->
<!--export default {-->
<!--  data: () => ({-->
<!--    links: [-->
<!--      'Dashboard',-->
<!--      'Messages',-->
<!--      'Profile',-->
<!--      'Updates'-->
<!--    ]-->
<!--  })-->
<!--}-->
<!--</script>-->

<style scoped>

</style>
