<template>
  <section>
    <v-parallax :src="hero" height="380">
      <v-layout column align-center justify-center>
        <div class="headline white--text mb-3 text-xs-center">
          Sudah memiliki project? Mulai membangun projek hari ini?
        </div>
        <em>Daftarkan projek anda dengan mudah</em>
        <v-btn class="pink accent-2 mt-5" dark large>
          Daftarkan projek
        </v-btn>
      </v-layout>
    </v-parallax>
  </section>
</template>

<script>
import Hero from '@/assets/img/index.jpeg'
export default {
  name: 'IndexCompanyQuote',
  data() {
    return {
      hero: Hero
    }
  }
}
</script>

<style scoped></style>
