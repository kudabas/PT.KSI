<template>
  <v-container class="abp">
    <v-row>
      <v-col cols="12" md="6">
        <v-img
          style="position: relative"
          src="@/assets/about_img.png"
          max-height="700"
          max-width="700"
        ></v-img>
      </v-col>
      <v-col cols="12" md="6" class="aus">
        
                <h1>About Us <v-icon>email</v-icon></h1>
        <h3>
          PT. Keberlanjutan Strategis Indonesia is a consulting company
          domiciled in Bandung City and was established on September 30, 2017
          based on Notary deed Number: -08- before Notary Indra Prayitno,
          S.H.,M.Kn. The purpose of establishing this consulting firm is to
          provide consulting services and research studies. Through an agreement
          with PT. Keberlanjutan Strategies Indonesia made a change in
          management, on April 22 2019, based on notarial deed Number -2- before
          Notary Indra Prayitno, S.H., M.Kn having the address at Pakar Barat
          Street, No. 9 B-Lt.1, Kabupaten Bandung 40198. As the amendment of the
          notarial deed was made, the new company management wanted to expand
          the company's service activities and services in the fields of
          Management Consulting Services, Consulting Services on Environmental
          Issues, Telematics, Survey Services, Study Services, Research and
          Assistance. Engineering, Training Services and Scientific Studies.
        </h3>
        <br />
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
.v-col.aus {
  padding-right: 90px;
  padding-left: 90px;
}
.v-container.abp {
  padding-top: 70px;
}
/* .v-container.abo {
  background-image: url("@/assets/bghome.png");
  background-size: 1950px 800px;
} */
</style>

<!-- <template>
  <div class="uhuy">
  <v-container flex>
    <v-row>
      <v-col cols="6">
        <v-img
          style="position: relative"
          src="@/assets/about_img.png"
          max-height="700"
          max-width="700"
        ></v-img>
      </v-col>
      <v-col cols="6">
        <h1>About Us</h1>
        <h2>
          PT. Keberlanjutan Strategis Indonesia is a consulting company
          domiciled in Bandung City and was established on September 30, 2017
          based on Notary deed Number: -08- before Notary Indra Prayitno,
          S.H.,M.Kn. The purpose of establishing this consulting firm is to
          provide consulting services and research studies.
        </h2>
        
          <v-btn tile dark class="text-green" variant="outlined">
            <router-link to="/"></router-link>
            <p>contact</p>
          </v-btn>
      
      </v-col>
    </v-row>
  </v-container>
</div>
</template>

<script>
export default {};
</script>

<style scoped>
.div.uhuy{
  padding: 100px;
}
</style> -->

        <!-- <router-link to="/about" custom v-slot="{ navigate }">
          <v-btn variant="outlined" rounded @click="navigate" role="link">
            <h3>Read more</h3>
          </v-btn>
        </router-link> -->