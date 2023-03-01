<template>
  <v-container class="abp">
    <h1 class="text-center">Vission And Mission</h1>
    <br />
    <v-row>
      <v-col cols="12" md="6">
        <h1>Vision</h1>
        <h3>
          PT. Keberlanjutan Strategis Indonesia, “to become a strategic partner
          in implementing sustainability practices, strong governance,
          scientific studies, Telematics”
        </h3>
        <br />
        <h1>Mission</h1>
        <h3><v-icon icon="fa-solid fa-circle fa-2xs" beat/>
          Assisting clients in developing an in-depth understanding of fundamental expectations related to the environment and strategic assessments in society
        </h3>
        <h3><v-icon icon="fa-solid fa-circle fa-2xs" /> Assisting our clients in contributing to the Sustainable Development Goals (SDGs) in the best possible way</h3>
        <h3><v-icon icon="fa-solid fa-circle fa-2xs" /> Assist clients in management consulting, telematics, and studies in both the private and government sectors.</h3>
        <h3><v-icon icon="fa-solid fa-circle fa-2xs" /> In implementing CSR and strategic sustainability, it is necessary to implement good governance (transparency, accountability, responsibility, independence and fairness) to ensure that CSR and sustainability are firmly implemented into business strategy and operations.</h3>
        <h3><v-icon icon="fa-solid fa-circle fa-2xs" /> Implementation of technology-based information systems</h3>
      </v-col>
      <v-col class="d-flex child-flex" cols="12" md="6">
        <v-img 
        class="mx-auto"
      
          style="position: relative"
          src="@/assets/visimisi_img.png"
          max-height="600"
          max-width="600"
        ></v-img>

        <br />
        <!-- <router-link to="/about" custom v-slot="{ navigate }">
                <v-btn 
                 variant="outlined" rounded @click="navigate" role="link">
                  <h3>Read more</h3>
                </v-btn>
              </router-link> -->
      </v-col>
    </v-row>
  </v-container>
</template>
  
  <script>
export default {};
</script>
  
  <style scoped>
  h1 {
  font-family: Montserrat;
}

h3 {
  font-family: Montserrat;
  font-style: Regular;

  color: #858383;
}
.v-icon{
  color: #3D8361;
}
/* .v-col.aus {
  padding-right: 90px;
  padding-left: 90px;
} */
.v-container.abp {
  padding-top: 70px;
}
/* .v-container.abo {
    background-image: url("@/assets/bghome.png");
    background-size: 1950px 800px;
  } */
</style>