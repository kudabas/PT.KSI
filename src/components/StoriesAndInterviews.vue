<template>
  <v-carousel cycle height="600" show-arrows="hover">
    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
      cover
    ></v-carousel-item>

    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
      cover
    ></v-carousel-item>

    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
      cover
    ></v-carousel-item>
    <v-carousel-item
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
      cover
    ></v-carousel-item>
  </v-carousel>
  <v-container flex>
    <div class="text-center">
      <h1>Stories and interviews</h1>
      <h3>
        Sed ut perspiciatis unde omnis iste natus error sit voluptatem
        accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab
        illo inventore veritatis et quasi architecto beatae vitae dicta sunt
        explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut
        odit aut fugit, sed quia consequuntur magni dolores eos qui ratione
        voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum
        quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam
        eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat
        voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam
        corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?
        Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse
        quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo
        voluptas nulla pariatur?"
      </h3>
    </div>
  </v-container>
</template>

<script>
export default {
  // data () {
  //   return {
  //     items: [
  //     {
  //         src: '@/assets/catra_logo.png',
  //       },
  //       {
  //         src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
  //       },
  //       {
  //         src: '@/assets/catra_logo.png',
  //       },
  //       {
  //         src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
  //       },
  //     ],
  //   }
  // },
};
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
</style>