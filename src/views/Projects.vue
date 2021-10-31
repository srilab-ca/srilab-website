<template>
<div>
    <h1>Past Projects</h1>
  <h2>
    🏎️ SRIL Gravity Car Challenge! 🏎️
  </h2>
  
  <p>
For summer 2021, SRIL hosted the Gravity Car Challenge, a series of workshops about computer-aided design (CAD), 3D printing, and physics that culminated in a race in which participants' gravity car designs were 3D printed and raced down a track. Cars were judged based on a combination of their race time and design creativity. In addition, a guest speaker was invited for a special workshop about studying engineering at university.
  
  </p>

  <h2>Gallery: </h2>
  <p>Thank you to our participants for submitting your creative designs for the summer 2021 SRIL Gravity Car Challenge! Have a look at our gallery to see what everyone submitted!</p>
  <v-container>
  <v-carousel hide-delimiters>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
  </v-container>
  <h2>Results</h2>
  <center>
  <v-img src="@/assets/Projects/results.png"
        max-height="800"
       max-width="800"
         >
         
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