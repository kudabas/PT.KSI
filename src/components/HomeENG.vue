<template>
  <v-container class="he">
    <v-row class="pa-5">
      <v-col cols="12" md="6">
        <div class="ma-16 pt-16">
          <h1 class="a">Developing</h1>
          <h1 class="a">solution for the future</h1>
          <h4 >
            We help our clients identify their issues, develope solutions and
            take action
          </h4>
          <br/>
          <v-btn
            href="https://api.whatsapp.com/send/?phone=6281120011644&text&type=phone_number&app_absent=0"
            variant="outlined"
            rounded
          >
            Contact Us
          </v-btn>
        </div>
      </v-col>
      <v-col cols="12" md="6">
        <v-img
          class="pt-10"
          style="position: relative"
          src="@/assets/hero_img.png"
          max-height="800"
          max-width="800"
        ></v-img>
      </v-col>
    </v-row>

    <!-- <v-row>
          <v-col cols="6" class="a">
            <div style="position: relative" class="a ">
               
            </div>
            <div style="position: relative" class="a ">
            
            </div>
            <div style="position: relative" class="b">
             
            </div>
            <div style="position: relative" class="b">
              develop solutions and take action
            </div>
            <router-link to="/about" custom v-slot="{ navigate }">
              <v-btn variant="outlined" rounded @click="navigate" role="link">
                <h2>Contact Us</h2>
              </v-btn>
            </router-link>
          </v-col>
          <v-col cols="6">
            <v-img
              style="position: relative"
              src="@/assets/hero_img.png"
              max-height="800"
              max-width="800"
            ></v-img>
          </v-col>
        </v-row> -->
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
.a {
  font-size: 4vw;
  color: white;
}
h4 {
  font-size: 1vw;
  color: white;
  /* background-image: url("@/assets/logo.svg"); */
}
@media (max-width: 991px){
  .a{
    font-size: 2rem;
  }
  h4 {
  font-size: 1rem;
  color: white;
  /* background-image: url("@/assets/logo.svg"); */
}
}
/* .v-col.a {
  padding-left: 50px;
  padding-top: 80px;
}
.v-col.b {
  padding-left: 50px;
  padding-top: 60px;
} */
.v-container.he {
  background-image: url("@/assets/bghome (1).png");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  max-width: 100%;
  padding-bottom: 140px;
  /* padding-top: 50px; */
}
/* .v-img{
  margin: auto;
} */
.v-btn:hover {
  background-color: #d6cda4;
  color: #3d8361;
}

.v-btn:focus {
  background-color: #d6cda4;
}

.v-btn:active {
  background-color: #d6cda4;
}
.v-btn {
  color: #d6cda4;
  text-transform: none !important;
}
</style>