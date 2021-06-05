<template>
  <v-app-bar
    app
    color="white"
    flat
  >
    <v-tabs
      centered
      class="ml-n9"
      color="grey darken-1"
    >
      <v-tab to="/" nuxt>
        About Us
      </v-tab>
      <v-tab to="/trips" nuxt>
        Our Trips
      </v-tab>
    </v-tabs>
  </v-app-bar>
</template>

<script>
export default {
  name: 'NavBar'
}

</script>

<style scoped>

</style>
