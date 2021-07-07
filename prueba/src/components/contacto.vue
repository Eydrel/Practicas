<template>
<v-container grid-list-md>
    <h1 class="text-center"> Contacto </h1>
    <v-layout row wrap>


        <v-flex xs12 sm6 md4   >
            <v-card
            class="mx-auto"
            max-width="600"
            align="center"
            >
                <v-img 
                src="@/assets/chatenvivo2.png">
                </v-img>
                   
                    <v-btn
                          text
                          color="teal accent-4"
                          href="http://edu.educacionbienestaritson.mx/cursos/">
                        Contactar
                           </v-btn>
                          
      </v-card>
        </v-flex>


 <v-flex xs12 sm6 md4   >
            <v-card
            class="mx-auto"
            max-width="600"
            align="center"
            >
                <v-img 
                src="@/assets/logo1.png">
                </v-img>
                        <v-btn
                          text
                          color="teal accent-4"
                          href="http://edu.educacionbienestaritson.mx/cursos/">
                        Contactar
                           </v-btn>
                          
      </v-card>
        </v-flex>

        
        <v-flex xs12 sm6 md4 >
            <v-card class="mx-auto"
            max-width="600"
            align="center"
            >
                <v-img 
                src="@/assets/whatsapp1.2.png">
                </v-img>
                   
      <v-btn 
          text
          color="teal accent-4"
          href="http://locatel.cdmx.gob.mx">
          Contactar
      </v-btn>

    <v-expand-transition>
      <v-card
        v-if="show"
        class="transition-fast-in-fast-out v-card--reveal"
        style="height: 100%;"
      >
        <v-card-text class="pb-0">
          <p class="text-h4 text--primary">
            Informacion Adicional
          </p>
          <p>late 16th century (as a noun denoting a place where alms were distributed): from medieval Latin eleemosynarius, from late Latin eleemosyna ‘alms’, from Greek eleēmosunē ‘compassion’ </p>
        </v-card-text>
        <v-card-actions class="pt-0">
          <v-btn
            text
            color="teal accent-4"
            @click="show = false"
          >
            Cerrar
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-expand-transition>
            </v-card>
        </v-flex>
    
      
    </v-layout>
</v-container>
</template>

<script>
  export default {
    data: () => ({
      mostrar: false,
      show: false,
      reveal: false,
      enseñar: false,
     
    }),
  }
</script>


<style >

.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}

</style>