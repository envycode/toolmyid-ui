<template>
  <div>
    <v-app dark>
      <section>
        <v-container grid-list-md>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <about-company-banner />
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <about-company-detail />
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </v-app>
  </div>
</template>

<script>
import AboutCompanyBanner from '@/components/about/company-banner/CompanyBanner'
import AboutCompanyDetail from '@/components/about/company-detail/CompanyDetail'
export default {
  name: 'About',
  components: {
    AboutCompanyBanner,
    AboutCompanyDetail
  },
  data() {
    return {}
  }
}
</script>

<style scoped></style>
