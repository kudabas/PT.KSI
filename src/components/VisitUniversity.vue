<template>
   <v-container flex>
    <div>
      <h1>Visit University</h1>
      <br/>
    </div>
    <v-row justify="center">
      <v-col cols="12" md="4" lg="4">
        <router-link to="/stories" custom v-slot="{ navigate }">
          <v-card @click="navigate" role="link" variant="outlined-white">
            <v-img
              class="align-end text-white"
              height="200"
              src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              cover
            >
            </v-img>
            <v-row>
              <v-col cols="11" md="11">
                <h2> Bill Walsh leadership lessons</h2>
            <h4> Like to know the secrets of transforming a 2-14 team into a 3x Super Bowl winning Dynasty?</h4>
          </v-col> 
          <v-col cols="1" md="1">
            <v-icon class="pt-5" icon="fa-solid fa-chevron-right fa-2xs" />

          </v-col>
        </v-row>  </v-card></router-link
        >
      </v-col>
      <v-col cols="12" md="4" lg="4"
        ><v-card variant="outlined-white">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            cover
          >
          </v-img>
          <v-card-title>Bill Walsh leadership lessons</v-card-title>
        </v-card> </v-col
      ><v-col cols="12" md="4" lg="4"
        ><v-card variant="outlined-white">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            cover
          >
          </v-img>
          <v-card-title>Bill Walsh leadership lessons</v-card-title>
        </v-card>
      </v-col>
    </v-row>
    <v-row>
        <v-col cols="12" md="4" lg="4">
        <router-link to="/about" custom v-slot="{ navigate }">
          <v-card @click="navigate" role="link" variant="outlined-white">
            <v-img
              class="align-end text-white"
              height="200"
              src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              cover
            >
            </v-img>
            <v-card-title>Bill Walsh leadership lessons</v-card-title>
          </v-card></router-link
        >
      </v-col>
      <v-col cols="12" md="4" lg="4"
        ><v-card variant="outlined-white">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            cover
          >
          </v-img>
          <v-card-title>Bill Walsh leadership lessons</v-card-title>
        </v-card> </v-col
      ><v-col cols="12" md="4" lg="4"
        ><v-card variant="outlined-white">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
            cover
          >
          </v-img>
          <v-card-title>Bill Walsh leadership lessons</v-card-title>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {

}
</script>

<style scoped>
.v-card:hover {
  background-color: #eef2e6;
  color: rgb(19, 19, 19);
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
</style>

