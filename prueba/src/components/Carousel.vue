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
            src: 'https://i.pinimg.com/originals/8f/86/d5/8f86d5fd68e23c7bb04a7bde3bf79f30.jpg',
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