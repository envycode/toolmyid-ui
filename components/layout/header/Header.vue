<template>
  <div>
    <v-toolbar color="pink accent-3">
      <v-toolbar-side-icon
        class="hidden-md-and-up"
        @click.stop="drawer = !drawer"
      ></v-toolbar-side-icon>
      <v-spacer>
        <img class="fx-icon" :src="icon" alt="Funxtion icon" />
        <strong>
          {{ title }}
        </strong>
      </v-spacer>
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn v-for="item in items" :key="item.title" :to="item.to" nuxt flat>
          <v-icon size="24px">{{ item.icon }}</v-icon> {{ item.title }}
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <v-navigation-drawer v-model="drawer" absolute temporary>
      <v-list class="pt-0" dense>
        <v-divider></v-divider>

        <v-list-tile v-for="item in items" :key="item.title" :to="item.to" nuxt>
          <v-list-tile-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-tile-action>

          <v-list-tile-content>
            <v-list-tile-title>{{ item.title }}</v-list-tile-title>
          </v-list-tile-content>
        </v-list-tile>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
import Icon from '@/assets/img/icon.png'
export default {
  name: 'LayoutHeader',
  data() {
    return {
      icon: Icon,
      items: [
        {
          icon: 'home',
          title: 'Home',
          to: '/'
        },
        {
          icon: 'info',
          title: 'About',
          to: '/about'
        }
      ],
      drawer: null,
      title: 'FUNXTION ID'
    }
  }
}
</script>

<style scoped>
.fx-icon {
  width: 26px;
  height: 30px;
  padding: 4px 1px;
  border: 1px solid black;
}
</style>
