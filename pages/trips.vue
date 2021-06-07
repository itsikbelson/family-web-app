<template>
  <v-main>
    <v-container>
      <v-card>
        <v-card-title class="headline">
          Pictures from our trips
        </v-card-title>
        <v-carousel>
          <v-carousel-item
            v-for="(item,i) in items"
            :key="i"
            reverse-transition="fade-transition"
            transition="fade-transition"
            eager
          >
            <v-img
              :src="item.src"
              eager
            />
          </v-carousel-item>
        </v-carousel>
      </v-card>
    </v-container>
  </v-main>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
        },
        {
          src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
        }
      ]
    }
  }
}
</script>
