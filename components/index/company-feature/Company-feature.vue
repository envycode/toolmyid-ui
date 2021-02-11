<template>
  <section>
    <v-layout column wrap class="my-5" align-center>
      <v-flex xs12 sm4 class="my-3">
        <div class="text-xs-center">
          <h2 class="headline">Langkah terbaik untuk memulai projek</h2>
          <span class="subheading">
            Desain, Efisien, Maintability
          </span>
        </div>
      </v-flex>
      <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout row wrap align-center>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="pink--text text--lighten-2">
                    color_lens
                  </v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">DESAIN</div>
                </v-card-title>
                <v-card-text>
                  Memulai suatu projek akan terasa mudah jika sudah tahu
                  gambaran dari project tersebut. Oleh sebab itu membuat desain
                  pada saat akan memulai dalam pembuatan projek sangat baik.
                  Selain itu, desain berperan penting juga pada pengalaman dari
                  penggunanya.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="pink--text text--lighten-2">
                    flash_on
                  </v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">EFISIENSI</div>
                </v-card-title>
                <v-card-text>
                  Efisiensi dapat dilakukan dalam melakukan suatu projek.
                  Sebagai contoh projek yang baik harus diketahui batas dari
                  pengerjaan projek tersebut. Sehingga dalam eksekusi projek
                  tersebut dapat dilakukan pengambilan keputusan tingkat
                  eksekusi pengerjaan projek.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="pink--text text--lighten-2">
                    build
                  </v-icon>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline text-xs-center">
                    MAINTABILITY
                  </div>
                </v-card-title>
                <v-card-text>
                  Maintability dari suatu projek sangat penting. Hal ini
                  digunakan dalam pemeliharaan serta pengembangan projek pada
                  tahap selanjutnya. Tingkat maintability juga mempengaruhi
                  kerja dalam tim. Semakin baik maintability maka permasalahan
                  project dapat selesai lebih cepat.
                </v-card-text>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-flex>
    </v-layout>
  </section>
</template>

<script>
export default {
  name: 'IndexCompanyFeature',
  data() {
    return {}
  }
}
</script>

<style scoped></style>
