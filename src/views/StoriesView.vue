<template>
  <v-app id="stories">
    <StoriesAndInterviews />
  </v-app>
</template>

<script>
import { defineComponent } from 'vue';
import StoriesAndInterviews from '@/components/StoriesAndInterviews.vue';

export default defineComponent({
  name: 'StoriesView',
  components: {
    StoriesAndInterviews,
}
});
</script>

<style>

</style>