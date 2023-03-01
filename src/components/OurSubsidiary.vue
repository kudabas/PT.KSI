<template>
  <v-container flex>
    <v-card class="mx-auto" max-width="1700" elevation="5">
      <v-row class="pa-5">
        <v-col cols="12" md="3">
          <div class="pa-10">
            

             <h1> Our subsidiary</h1>
            <h4> Below are some of the our subsidiary</h4>
          </div>
          <!-- <h2 ></h2>
            <br />
            <h4>Below are some of the our Division Business</h4> -->
        </v-col>
        <v-col cols="12" md="3">
          <v-img
          class="pa-10"

            style="position: relative"
            src="@/assets/ADPSI_Logo.png"
            max-height="800"
            max-width="800"
          ></v-img>
        </v-col>
        <v-col cols="12" md="3">
          <v-img
          class="pa-10"

            style="position: relative"
            src="@/assets/Jari_LOgo.png"
            max-height="800"
            max-width="800"
          ></v-img>
        </v-col>
        <v-col cols="12" md="3">
          <v-img
          class="pa-10"

            style="position: relative"
            src="@/assets/LSP_Logo.png"
            max-height="350"
            max-width="350"
          ></v-img>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
.v-container {
  padding-top: 50px;
  padding-bottom: 50px;
}
h1 {
  font-family: Montserrat;
}
h2 {
  font-family: Montserrat;
}

h4 {
  font-family: Montserrat;
  font-style: Regular;

  color: #858383;
}

/* @media (max-width: 991px){
  h1{
    font-size: 1rem;
  }
  h4 {
  font-size: 1rem;
  
}
} */
.v-img:hover {
  background-color: #eef2e6;
}
</style>
