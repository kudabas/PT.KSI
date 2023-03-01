<template>
  <v-app>
    <div>
     <div> <NavBar /> </div>
      <router-view/>
     <div> <FooterKSI /> </div> 
    </div>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
import FooterKSI from './components/FooterKSI.vue';

export default {
  name: 'App',
  components: { NavBar, FooterKSI
  },
  data: () => ({
    //
  }),
}
</script>
