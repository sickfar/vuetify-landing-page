<template>
  <v-footer dark padless>
    <v-card flat tile class="secondary white--text text-center">
      <v-card-text>

          <v-icon size="24px"   class="mx-4 white--text" v-for="(icon, i) in icons" :key="i">{{ icon.text }}</v-icon>
    
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Algunas de las tecnologias utilizadas en nuestros proyectos.
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>FixyTech</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
.v-card {
  width: 100%;
}
</style>

<script>
export default {
  data: () => ({
    icons: [
      {
        text: "fa-brands fa-js",
        link: "",
        nombre:"JAVASCRIPT"
      },
      {
        text: "fa-brands fa-vuejs",
        link: "",
        nombre:"VUEJS"
      },
      {
        text: "fa-brands fa-php",
        link: "",
        nombre:""
      },
      {
        text: "fa-brands fa-laravel",
        link: "",
        nombre:""
      },
      {
        text: "fa-brands fa-android",
        link: "https://instagram.com/joabson_arley/",
        nombre:""
      },
      {
        text: "fa-brands fa-github",
        link: "",
        nombre:""
      }
    ],
  }),
};
</script>
