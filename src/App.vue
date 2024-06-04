<template>
  <v-app>
    <v-main>
        <v-app-bar app color="primarary">
            <v-toolbar-title>Most used Words</v-toolbar-title>
        </v-app-bar>
        <HomePage />
    </v-main>
  </v-app>
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',

  components: {
    HomePage
    
  },

  data: () => ({
    //
  }),
}
</script>
