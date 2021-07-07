<template>
    
<container>

  <v-parallax src="https://fondosmil.com/fondo/71316.png"></v-parallax>
<h1 class="text-center"> Quienes Somos </h1>
<v-slider disabled
dense
hint="im a hint"
max="50"
min="-50"
></v-slider>
<v-card
class="d-flex justify-space-around mb-6"

>

<h2>
Somos un grupo de investigadores de varias universidades interesados en difundir los resultados
de nuestras investigaciones al servicio de nuestra comunidad.

</h2>

<v-slider disabled
hint="im a hint"
max="50"
min="-50"
vertical
></v-slider>
<v-card-text class="text-justify">
  
</v-card-text>
</v-card>

<Footer/>
</container>
</template>
<script>
 
 import Footer from '../components/Footer'
export default {
  components: {
     Footer,
    },
}
</script>

<style scoped>

</style>