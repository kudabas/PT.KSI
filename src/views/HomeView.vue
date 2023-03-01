<template>
  <v-app id="home">
          <HomeENG />
          <OurBusinessENG />
          <HowBusinessENG />
          <AboutUsENG />
          <OurSubsidiary />
          <CorporateSocial />
          <VisitUniversity />
  </v-app>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HomeENG from '@/components/HomeENG.vue';
import OurBusinessENG from '@/components/OurBusinessENG.vue';
import HowBusinessENG from '@/components/HowBusinessENG.vue';
import OurSubsidiary from '@/components/OurSubsidiary.vue';
import AboutUsENG from '@/components/AboutUsENG.vue';
import CorporateSocial from '@/components/CorporateSocial.vue';
import VisitUniversity from '@/components/VisitUniversity.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HomeENG,
    OurBusinessENG,
    HowBusinessENG,
    OurSubsidiary,
    AboutUsENG,
    CorporateSocial,
    VisitUniversity
},
});
</script>
