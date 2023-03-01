<template>
  <v-app id="about">
    <AboutUsPageENG/>
    <VissionMissionPage/>
  </v-app>
</template>

<script>
import AboutUsPageENG from '@/components/AboutUsPageENG.vue';
import VissionMissionPage from '@/components/VissionMissionPage.vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'AboutView',
  components: {
    AboutUsPageENG,
    VissionMissionPage
}
});
</script>

    VissionMissionPage