<template>
  <div id="footer">
    <footer class="site-footer">
      <v-container flex>
        <hr />
        <v-row class="mb-1" justify="center" no-gutters>
          <v-col cols="12" md="3">
            <v-img
              style="position: relative"
              src="@/assets/ksiputih.png"
              max-height="200"
              max-width="200"
            >
            </v-img>
            <!-- <v-row class="ficon">
              <v-col cols="sm-2 col-md-2">
                <v-img
                  style="position: relative"
                  src="@/assets/legal_icon.png"
                  max-height="100"
                  max-width="100"
                ></v-img
              ></v-col>
              <v-col cols="sm-2 col-md-2">
                <v-img
                  style="position: relative"
                  src="@/assets/Instagram_icon.png"
                  max-height="50"
                  max-width="50"
                ></v-img
              ></v-col>
              <v-col cols="sm-2 col-md-2">
                <a
                  href="https://www.figma.com/file/nFLwpTGi9Z0dBnLIKh21qV/Untitled?node-id=0%3A1&t=x0kbXrvzcFLLm4qS-0"
                >
                  <v-img
                    style="position: relative"
                    src="@/assets/Facebook_icon.png"
                    max-height="50"
                    max-width="50"
                  ></v-img
                ></a>
              </v-col>
              <v-col cols="sm-2 col-md-2">
                <v-img
                  style="position: relative"
                  src="@/assets/wa_icon.png"
                  max-height="50"
                  max-width="50"
                ></v-img
              ></v-col>
            </v-row> -->
            <v-row class="mb-1" no-gutters>
              <v-col cols="2" >
                <v-img
                class="mx-auto"
                  style="position: relative"
                  src="@/assets/legal_icon.png"
                  max-height="30"
                  max-width="30"
                ></v-img>
              </v-col>
              <v-col cols="2" >
                <a href="https://www.instagram.com/strategis.co/" target="blank_">
                <v-img
                class="mx-auto"
                  style="position: relative"
                  src="@/assets/Instagram_icon.png"
                  max-height="30"
                  max-width="30"
                ></v-img></a>
              </v-col>
              <br />
              <v-col cols="2" >
                <a href="https://www.facebook.com/keberlanjutan.keberlanjutan" target="blank_">
                <v-img
                class="mx-auto"
                  style="position: relative"
                  src="@/assets/Facebook_icon.png"
                  max-height="30"
                  max-width="30"
                ></v-img> </a>
                 </v-col
              ><v-col cols="2" >
                <a
                  href="https://api.whatsapp.com/send/?phone=6281120011644&text&type=phone_number&app_absent=0" target="blank_"
                >
                  <v-img
                  class="mx-auto"
                    style="position: relative"
                    src="@/assets/wa_icon.png"
                    max-height="30"
                    max-width="30"
                  ></v-img
                ></a>
              </v-col>
            </v-row>
            <br />
          </v-col>
          <v-col cols="12" md="3" class="ftxt">
            <div>
              <h2>Company</h2>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> About Us</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Our Division</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Our Subsidiaries</h4>
            </div></v-col
          >
          <v-col cols="12" md="3" class="ftxt">
            <div>
              <h2>What We Do</h2>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Web Development</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Mobile App Development</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Annual REport and Sustainability</h4>
              
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Sustainability Report Assurance</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> GCG Assesment</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Business Research and Development</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Sustainable Finance</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Information Systems Analysis</h4>
              <h4><v-icon icon="fa-solid fa-chevron-right fa-2xs" /> Brand Management</h4>
            </div>
          </v-col>
          <v-col cols="12" md="3" class="ftxt">
            <div>
              <h2>Contact</h2>

              <h4><v-icon icon="fa-solid fa-location-dot fa-lg" />
                Jl. Monteron No. 1A. RT 06, RW. 11 Kel. Sukaluyu, Kec.
                Cibeunying Kaler. 40123
              </h4>
              <br/>
              <h4><v-icon icon="fa-solid fa-envelope-open-text fa-lg" />
                     keberlanjutanstrategis@gmail.com info@keberlanjutan.com
                support@keberlanjutan.com
              </h4>
              <br/>
              <h4><v-icon icon="fa-solid fa-phone fa-lg" />
                Office: (022) 2051-1881, (022) 20466451
              </h4>
              <br/>
              <h4><v-icon icon="fa-solid fa-mobile-screen-button fa-lg" />
                Mobile: +62 821 1628
                1143
              </h4>
            </div>
          </v-col>
        </v-row>
        <br />
        <hr />
        <div class="text-center pt-5">
          <a href="https://www.strategis.co.id/">
            <h5>Copyright © 2023 PT. Keberlanjutan Strategis Indonesia</h5></a
          >
        </div>
      </v-container>
    </footer>
  </div>
</template>
  
  <script>
export default {};
</script>

  <style scoped>
a {
  text-decoration: none;
}
/* .v-row.ficon {
  padding-left: 5px;
  padding-block-start: 5px;
} */
h4 {
  font-family: Montserrat;
  font-style: Regular;
}
h5 {
  font-family: Montserrat;
  font-style: Regular;
  color: #d6cda4;
}
h2 {
  color: #d6cda4;
  padding-top: 30px;
  padding-bottom: 20px;
  font-family: Montserrat;
}

.v-col.ftxt {
  padding-left: 100px;
}
.site-footer {
  background: linear-gradient(500deg, #1c6758 15%, #3d8361 50%);
  padding: 45px 0 20px;
  font-size: 15px;
  line-height: 24px;
  color: #ffffff;
}
</style>
  
  