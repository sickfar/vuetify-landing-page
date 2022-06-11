<template>

  <section id="download">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <v-row align="center" justify="center">
            <v-col sm="4" class="hidden-xs-only">
              <v-img
                src="@/assets/img/ill2.svg"
                class="d-block ml-auto mr-auto"
                max-width="350px"
              />
            </v-col>
            <v-col cols="12" sm="8" class="white--text text-left">
              <h1 class="font-weight-light display-2 mb-2">
                ¿Por qué elegirnos?
              </h1>
              <h4 class="font-weight-light">
                <br />
                Porque aseguramos el cumplimiento de los plazos establecidos.
                <br />
                Porque trabajamos con transparencia, confianza y empatía. <br />
                Porque tratamos a cada cliente como si fuera el único. <br />
                Porque su proyecto es nuestro proyecto.<br />
              </h4>
              <v-btn
                rounded
                outlined
                href="https://t.me/FixyTech"
                target="_blank"
                large
                color="white"
                class="mt-4"
              >
                <v-icon class="mr-2"> fa-brands fa-telegram </v-icon>
                Contactenos
              </v-btn>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<style scoped>
#download {
  background-image: url("~@/assets/img/bgDownload.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: 500px;
}

#download .container,
#download .row {
  height: 100%;
}
</style>