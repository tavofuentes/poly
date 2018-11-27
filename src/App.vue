<template>
  <v-app>
    <v-toolbar
      color="amber darken-3"
      dark
    >
      <v-toolbar-side-icon></v-toolbar-side-icon>
      <v-toolbar-title>Poly</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn icon>
        <v-icon>search</v-icon>
      </v-btn>
    </v-toolbar>

    <CardArchive/>
  </v-app>
</template>

<script>
import CardArchive from './components/CardArchive'

export default {
  name: 'App',
  components: {
    CardArchive
  },
  data () {
    return {
      //
    }
  }
}
</script>
