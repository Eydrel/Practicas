<template>
<div>
<v-carousel

height="550"
class="d-lg-none d-xs-flex"
hide-delimiter-background
>
     <v-carousel-item >
     <v-img src="@/assets/celularPortada.png">
      </v-img>
    </v-carousel-item>
  </v-carousel>
<div>

  <v-carousel  class="d-none d-lg-block">
 <v-carousel-item
 
      reverse-transition="fade-transition"
      transition="fade-transition">
      <v-img src="@/assets/portada.png">
      </v-img>
    </v-carousel-item>
  </v-carousel>
</div>
</div>

 
</template>

<script>
  export default {
    data: () => ({
      model: 0,
      colors: [
        'primary',
        'secondary',
        'yellow darken-2',
        'red',
        'orange',
      ],
    }),
  }
</script>

   