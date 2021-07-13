<template>

<v-container>
<v-flex lg>
    <div class="d-none d-lg-block">
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
            </div>
            </v-flex>
        <br>

    <!-- Despues de este div, es la version de vista para pantallas menores a LG -->
    <v-flex class="d-lg-none d-md-flex">
    <div>
        <v-card
        
        max-width="1400"
        outlined
        class="mx-auto"
    >
        <v-list-item three-line>

        <v-list-item-content>

            <div class="text-overline mb-4">
                Adultos Mayores
            </div>

        <v-list-item-title class="body-1 "><strong>
            Envejecimiento Activo - Curso
        </strong>
        </v-list-item-title>

        <v-list-item-subtitle class="body-1">
                 Nuestra sociedad ha obtenido grandes éxitos con los avances científicos  y
        </v-list-item-subtitle>

         <v-list-item-subtitle class="body-1">
               tecnológicos de las últimas décadas.  
        </v-list-item-subtitle>

        </v-list-item-content>

        </v-list-item>

        <v-card-actions>
        <v-btn class="ma-2" rounded large outlined color="pink" href="http://edu.educacionbienestaritson.mx/cursos/?redirect=0">IR A CURSOS</v-btn>
        </v-card-actions>
        
        </v-card>
        <br>
    
        <v-card
            max-width="1400"
            outlined
            class="mx-auto"
        >
        
        <v-list-item three-line>
        <v-list-item-content>
            <div class="text-overline mb-4">
            Educacion - Alumnos
            </div>
        <v-list-item-title class="body-1 "><strong>
            Cursos Educativos Para Alumnos
        </strong>
        </v-list-item-title>

        <v-list-item-subtitle class="body-1">
                 Nuestra sociedad ha obtenido grandes éxitos con los avances científicos  y
        </v-list-item-subtitle>

        <v-list-item-subtitle class="body-1">
               tecnológicos de las últimas décadas.  
        </v-list-item-subtitle>

        </v-list-item-content>

        </v-list-item>

        <v-card-actions>
        <v-btn class="ma-2" rounded large outlined color="pink" href="http://edu.educacionbienestaritson.mx/cursos/?redirect=0">IR A CURSOS</v-btn>
        </v-card-actions>
        </v-card>
    
    </div>
  </v-flex>
  

</v-container>
</template>


<script>
export default {

}
</script>