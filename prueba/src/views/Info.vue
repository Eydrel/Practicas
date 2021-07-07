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
<h1 class="text--secondary">
  <p class="text-justify">
Somos un grupo de investigadores de varias universidades interesados en difundir los resultados
de nuestras investigaciones al servicio de nuestra comunidad.
  </p>
</h1>
<h2 class="text--secondary">
  <p class="text-justify">
El Inicio del proyecto comenzo con la idea de proveer Información necesaria y útil para personas de la tercera edad, 
acerca de temas recientes y situaciones importantes, acerca del virus sars cov 2 (Covid-19), en donde personas que le es 
dificíl encontrar Información veridica, pudieran informarse y cuidarse, como también tuvieran conocimiento acerca de su salud
mental.
  </p>
</h2>
  
    
  <equipo/>
<Footer/>
</container>
</template>
<script>
 
 import Footer from '../components/Footer'
 import equipo from '../components/equipo.vue'
export default {
  components: {
     Footer,equipo,
    },
}
</script>

<style scoped>

</style>