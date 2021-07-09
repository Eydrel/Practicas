<template>
      
        <v-layout row wrap >
            <v-flex  md8  
            class="mx-10"
            >
               <card
             
               >
                    <h1>
                    Somos un grupo de investigadores de varias universidades interesados en difundir los resultados
                    de nuestras investigaciones al servicio de nuestra comunidad.
                    </h1>
                    <br>
                        <h2 class="text--secondary">
                            <p class="text-justify">
                            El grupo de investigación de Actores y Procesos educativos de ITSON, iniciaron con la propuesta de generar una plataforma para realizar una devolución de los resultados de la investigación para diferente tipo de público, y ofertar procesos de formación de competencias sencillas y específicas que aportaran al bienestar personal, colectivo y ambiental. Se generaron tres áreas de Educación, Adultos Mayores y Salud. En estas temáticas se tienen alianzas con investigadores de otras instituciones de educación del país que se han sumado a este esfuerzo y colaboran en algunas de estas áreas. 
                            </p>
                        </h2>
                        <br>
                        <h2 class="text--secondary">
                        <p class="text-justify"> 
                        De la Universidad de Sonora se ha generado el área de Sustentabilidad dando paso a la aportación para el cuidado, 
                        difusión de resultados de investigación y formación de competencias para la sustentabilidad. 
                        Sin duda una valiosa colaboración 
                        con su área específica y de la cual otros investigadores colaboran. 
                        </p>
                        </h2>
                 </card>
            </v-flex>
    <v-flex md3 >
        <v-card
            max-width="500"
            height="520"
             class="mx-2"
            >
         <v-system-bar lights-out></v-system-bar>
            <v-carousel
                height="500">
                <v-carousel-item
                    v-for="(item,i) in items"
                    :key="i"
                     :src="item.src"
                    reverse-transition="fade-transition"
                    transition="fade-transition"
                    ></v-carousel-item>
            </v-carousel>
        </v-card>    
        </v-flex>
        </v-layout>
    
</template>

<script>
export default {
     data () {
    return {
        items: [
          {
            src: 'https://scontent.fcen1-1.fna.fbcdn.net/v/t1.6435-9/151205759_3663686247083296_3271210901438188425_n.jpg?_nc_cat=111&ccb=1-3&_nc_sid=e3f864&_nc_eui2=AeFi0Qh0Cgw51meMbyd6DgnW1j0xLyqoT4vWPTEvKqhPixC8eLZVRcG1W-75qsjiLqOUK3ZLxvAB1YUg0VjJZ9f3&_nc_ohc=i6PtJnYZYZgAX9dXgcH&_nc_ht=scontent.fcen1-1.fna&oh=6e0bb4ec01885ad02e5b1ea0fdc1e3d9&oe=60ECF06E',
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
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
          },
        ],
      }
    }
}
</script>

<style scoped>

</style>