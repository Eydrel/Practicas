<template>
  <v-footer
    color="grey lighten-3"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
      <v-btn
        v-for="link in links"
        :key="link"
        color="black"
        text
        rounded
        class="my-2"
      >
        {{ link }}
      </v-btn>
      <v-col
      color=""
        class="grey lighten-4 py-4 text-center black--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Neo-Development</strong>
      </v-col>
    </v-row>
  </v-footer>

  
</template>

<script>
  export default {
    data: () => ({
      links: [
        'Home',
        'About Us',
        'Team',
        'Services',
        'Blog',
        'Contact Us',
      ],
    }),
  }
</script>