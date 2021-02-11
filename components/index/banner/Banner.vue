<template>
  <section>
    <v-parallax :src="hero" height="600" alt="funxtion image">
      <v-layout column align-center justify-center class="white--text">
        <img :src="icon" alt="Funxtion id image" height="200" />
        <h1 class="white--text mb-2 display-1 text-xs-center">
          FUNXTION ID
        </h1>
        <div class="subheading mb-3 text-xs-center">
          Kenalin projek semakin mudah
        </div>
        <v-btn class="pink accent-2 mt-5" dark large>
          Mulai Sekarang
        </v-btn>
      </v-layout>
    </v-parallax>
  </section>
</template>

<script>
import Hero from '@/assets/img/index.jpeg'
import Icon from '@/assets/img/icon.png'
export default {
  name: 'IndexBanner',
  data() {
    return {
      hero: Hero,
      icon: Icon
    }
  }
}
</script>

<style scoped></style>
