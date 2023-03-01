<template>
  <v-container flex id="how">
    <div class="title text-center">
      <h1>How can we help your Business ?</h1>
      <h4>
        We build readymade websites, mobile applications, Study and Research,
        and Assessment
      </h4>
      <br/>
    </div>
    <v-row justify="center">
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/WB.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Website Development</h3>
          <br />
          <h4>Website Development, Solution for your business</h4>
          <br/>
          <br/>          
          </v-card
        >
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group82.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Mobile App Development</h3>
          <br />
          <h4 >Mobile application development solutions for your business </h4>
          <br/>
          <br/>
          </v-card
        >
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group83.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Business Research and Development</h3>
          <br />
          <h4>help solve problems, increase knowledge, make better interpretations and discover new facts.</h4>
          </v-card
        >
      </v-col>
    </v-row>
    <v-row justify="center">
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group84.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Sustainability Report Assurance</h3>
          <br />
          <h4>In providing guarantees for the Sustainability Report, an independent party is needed to provide it</h4>
          <h4 class="ttmbh" >.</h4>
          </v-card
        >
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group87.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Sustainable Finance</h3>
          <br/>
          <h4>offering training related to the implementation of sustainable finance assisting in the preparation of the Sustainable Finance Action Plan (RAKB)</h4>
          </v-card
        >
        
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group86.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Annual Report and Sustainability Report</h3>
          <br />
          <h4 >The annual report is prepared using the Annual Report Award (ARA) criteria</h4>
          <br/>
        </v-card
        >
      </v-col>
    </v-row>
    <v-row justify="center">
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10  text-center" >
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group85.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>GCG Assesment</h3>
          <br />
          <h4 >Good Corporate Governance Assessment for companies within BUMN uses instruments that have been developed by the Ministry of BUMN</h4>
          </v-card
        >
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center" >
          <v-img
            class=" mx-auto"
            style="position: relative"
            src="@/assets/Group88.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Information Systems Analysis</h3>
          <br />
          <h4>solving a problem by identifying and evaluating problems, opportunities, obstacles that occur</h4>
          <h4 class="ttmbh" >.</h4>
          </v-card
        >
      </v-col>
      <v-col cols="12" md="3" lg="3" class="pa-10">
        <v-card class="pa-10 text-center"  elevation="5">
          <v-img
            class="mx-auto"
            style="position: relative"
            src="@/assets/Group89.png"
            max-height="150"
            max-width="150"
          ></v-img>
          <br/>
          <h3>Brand Management</h3>
          <br />
          <h4>Assisting clients in compiling a Brand Management Strategy to increase the value generated</h4>
          <h4 class="ttmbh" >.</h4>
       </v-card
        >
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style scoped>
.v-container {
  padding-top: 100px;
}
h1{
  font-family: Montserrat;
}
h3{
  font-family: Montserrat;
  font-weight: bold;
}

h4 {
  font-family: Montserrat;
font-style: Regular;
font-weight:normal;

  color: #858383;
}

h4.ttmbh{
  color:white;
}

.v-card:hover {
  background-color: #eef2e6;
  color: rgb(19, 19, 19);
}
.v-img {
  padding-top: px;
}
.v-card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>