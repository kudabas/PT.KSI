<template>
  <v-container>
    <v-row class="pa-5">
      <v-col cols="12" md="6" class="text-center">
        <v-img
          style="position: relative"
          src="@/assets/about_img.png"
          max-height="800"
          max-width="800"
        ></v-img>
      </v-col>
      <v-col cols="12" md="6">
        <h1>About Us</h1>
        <h3>
          PT. Keberlanjutan Strategis Indonesia is a consulting company
          domiciled in Bandung City and was established on September 30, 2017
          based on Notary deed Number: -08- before Notary Indra Prayitno,
          S.H.,M.Kn. The purpose of establishing this consulting firm is to
          provide consulting services and research studies.
        </h3>
        <br />
        <router-link to="/about" custom v-slot="{ navigate }">
          <v-btn variant="outlined" rounded @click="navigate" role="link">
            <h2 class="uhuy">Read more</h2>
          </v-btn>
        </router-link>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
h2.uhuy {
  font-family: Montserrat;
  font-style: Regular;

  color: #1c6758;
}
h2.uhuy:hover {
  color: floralwhite;
}

h1 {
  font-family: Montserrat;
}

h3 {
  font-family: Montserrat;
  font-style: Regular;

  color: #858383;
}
/* .v-container.abo {
  background-image: url("@/assets/bghome.png");
  background-size: 1950px 800px;
} */
.v-btn {
  color: #1c6758;
  text-transform: none !important;
}
.v-btn:hover {
  background-color: #1c6758;
  color: floralwhite;
}
</style>