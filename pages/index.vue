<template>
  <div>
    <v-app dark>
      <banner />
      <company-feature />
      <company-quote />
      <section>
        <v-container grid-list-md>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <company-info />
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <contact-us />
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </v-app>
  </div>
</template>

<script>
import Banner from '@/components/index/banner/Banner'
import CompanyFeature from '@/components/index/company-feature/Company-feature'
import CompanyQuote from '@/components/index/company-quote/Company-quote'
import CompanyInfo from '@/components/index/company-info/Company-info'
import ContactUs from '@/components/index/contact-us/Contact-us'
export default {
  name: 'Index',
  components: {
    Banner,
    CompanyFeature,
    CompanyQuote,
    CompanyInfo,
    ContactUs
  },
  data() {
    return {}
  }
}
</script>
