<template>
  <div class="container">
    <div class="card" v-for="card in cards" :key="card.id"></div>
  </div>
  <ScrollGrid></ScrollGrid>
  <NuxtWelcome></NuxtWelcome>
</template>

<script>
import gsap from 'gsap'
import ScrollGrid from "@/components/animations/ScrollGrid";

export default {
  components: {
    ScrollGrid
  },
  data() {
    return { cards: [1, 2, 3, 4, 5, 6] }
  },
  mounted() {
    gsap.from('.card', {
      repeat: -1,
      duration: .7,
      stagger: .1,
      y: -150
    })
  }
}
</script>

<style>
.container{
  display:flex;
  flex-wrap:wrap;
  justify-content:space-evenly;
  width:400px;
  margin:20px auto}

.card{
  width:50px;
  height:50px;
  background:dodgerblue}
</style>
