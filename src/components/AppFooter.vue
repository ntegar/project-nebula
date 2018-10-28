<template>
  <v-footer
    dark
    height="auto"
  >
    <v-flex
      flat
      tile
      class="lighten-1 black--text text-xs-center" style="background: #6d6f72;"
    >
      <v-card-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-3 white--text"
          icon
        >
          <v-icon size="24px">{{ icon }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        Made with ❤️ by <strong>Nabil Tegar</strong>
      </v-card-text>
    </v-flex>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'fab fa-facebook',
        'fab fa-twitter',
        'fab fa-google-plus',
        'fab fa-linkedin',
        'fab fa-instagram'
      ]
    })
  }
</script>