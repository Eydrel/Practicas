<template>
<v-carousel

height="550"

hide-delimiter-background
>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
 
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://www.paho.org/sites/default/files/styles/flexslider_full/public/2020-03/blue-covid-banner.jpg?h=96546727&itok=xDLAoRJF',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg',
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    },
  }
</script>