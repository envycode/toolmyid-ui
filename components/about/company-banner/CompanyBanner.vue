<template>
  <v-layout justify-space-around>
    <v-img :src="icon" alt="Funxtion ID image"></v-img>
  </v-layout>
</template>

<script>
import Icon from '@/assets/img/icon.png'
export default {
  name: 'AboutCompanyBanner',
  data() {
    return {
      icon: Icon
    }
  }
}
</script>

<style scoped></style>
