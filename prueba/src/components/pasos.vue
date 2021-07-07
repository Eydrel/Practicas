<template>
<v-container grid-list-md-lg>
  <div class="d-lg-none">

  <v-stepper
    v-model="e6"
    vertical
  >
   
    <v-stepper-step
      :complete="e6 > 1"
      step="1"
      
        max-width="300"
        
    >
   
      Aprende A Cuidarte
      <small>Primer paso</small>
    </v-stepper-step>

    <v-stepper-content step="1">
      <v-card
        
       class="mb-1"
        height="280px"
      >
        <v-img 
                src="@/assets/diabetes.jpg">
                </v-img>
                <v-spacer></v-spacer>
               <v-card-text>
                   <span>Alimentate bien y Haz Ejercicio</span>
                   <span>Alimentate bien y Haz Ejercicio</span>
                   <span>Alimentate bien y Haz Ejercicio</span>
               </v-card-text>
        </v-card>

      <v-btn
        
        color="shades"
        @click="e6 = 2"
      >
        Continue
      </v-btn>
      <v-btn text>
        Cancel
      </v-btn>
    </v-stepper-content>

    <v-stepper-step
      :complete="e6 > 2"
      step="2"
    >
      Configure analytics for this app
    </v-stepper-step>

    <v-stepper-content step="2">
      <v-card
        color="grey lighten-1"
        class="mb-12"
        height="200px"
      ></v-card>
      <v-btn
        color="primary"
        @click="e6 = 3"
      >
        Continue
      </v-btn>
      <v-btn text>
        Cancel
      </v-btn>
    </v-stepper-content>

    <v-stepper-step
      :complete="e6 > 3"
      step="3"
    >
      Select an ad format and name ad unit
    </v-stepper-step>

    <v-stepper-content step="3">
      <v-card
        color="grey lighten-1"
        class="mb-12"
        height="200px"
      ></v-card>
      <v-btn
        color="primary"
        @click="e6 = 4"
      >
        Continue
      </v-btn>
      <v-btn text>
        Cancel
      </v-btn>
    </v-stepper-content>

    <v-stepper-step step="4">
      View setup instructions
    </v-stepper-step>
    <v-stepper-content step="4">
      <v-card
        color="grey lighten-1"
        class="mb-12"
        height="200px"
        
      ></v-card>
      <v-btn
        color="primary"
        @click="e6 = 1"
      >
        Repetir
      </v-btn>
      <v-btn
      color="error"
      @click="e6 = false"
      >
        Cancel
      </v-btn>
    </v-stepper-content>
  </v-stepper>
  </div>
</v-container>
</template>

<script>
  export default {
    data () {
      return {
        e6: 1,
      }
    },
  }
</script>