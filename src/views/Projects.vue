<template>
  <div>
    <h1>Current Project</h1>
    <h2>
      🚀 SRIL 2022 Planetary Exploration Challenge 🚀
    </h2>

    <p>
      On a distant planet, a rover awaits your command to begin exploration of a new planet's surface! SRIL's 2022
      Planetary Exploration challenge hopes to explore some of the objectives, and challenges faced by space agencies
      when exploring the uncharted terrain of extraterrestrial bodies.
    </p>

    <div class="text-center">
      <v-btn color="white" text rounded class="my-2" justify="center">
        <a target="_blank" href="https://forms.gle/o67NyZPMf6NfjEfr9" class="title">Register now</a>
      </v-btn>
    </div>

    <center>
      <v-img src="@/assets/Projects/SPEC_Poster.png" contain max-height="80vh">

      </v-img>
    </center>

  </div>
</template>

<script>
export default {
    data () {
      return {
        items: [
          {
            src: require('../assets/Projects/car1.jpg'),
          },
          {
            src: require('../assets/Projects/car2.jpg'),
          },
          {
            src: require('../assets/Projects/car3.jpg'),
          },
          {
            src: require('../assets/Projects/car4.jpg'),
          },
          {
            src: require('../assets/Projects/car5.jpg'),
          },
          {
            src: require('../assets/Projects/car6.jpg'),
          },
          {
            src: require('../assets/Projects/car7.jpg'),
          },
          {
            src: require('../assets/Projects/car8.jpg'),
          },
          {
            src: require('../assets/Projects/car9.jpg'),
          },
        ],
      }
    },
  }
</script>

<style>

</style>