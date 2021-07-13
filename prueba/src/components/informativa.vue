<template>

<v-container>
<v-flex>
    <div>
        <v-card
            max-width="1400"
            outlined
            class="mx-auto"
        >
        <v-list-item three-line>
           
            <v-list-item-content>
                <div class="text-overline mb-4">
                Salud
                </div>
            
            <v-list-item-title class="text-h5 mb-1">
                Detección temprana de diabetes
            </v-list-item-title>
            
            <v-list-item-subtitle class="text-h6 mb-1">
                  En la mayoría de los casos, la diabetes  tipo  2  se  atribuye  a  una  combinación  de resistencia a la insulina y fracaso de las células beta,pero no está claro en que medida cada uno de estos factores contribuye al desarrollo de la enfermedad
            </v-list-item-subtitle>

            </v-list-item-content>
                     
            <v-list-item-avatar
                tile
                height="200"
                size="200"
            ><v-img  src="@/assets/diabetes1.jpg"></v-img></v-list-item-avatar>
            </v-list-item>

            <v-card-actions>
            <v-btn class="ma-2" rounded large outlined color="blue" href="https://medlineplus.gov/spanish/diabetes.html">SABER MAS ...</v-btn>
            </v-card-actions>

            </v-card>

        <br>
  
    </div>
</v-flex>
</v-container>
</template>


<script>
export default {

}
</script>