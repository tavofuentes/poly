<template>
  <v-container
    fluid
  >
    <v-layout row wrap>
      <v-flex xs12>
        <Card />
      </v-flex>
    </v-layout>
    <!-- <v-layout row wrap>
      <v-flex>
        <v-btn fab dark small color="primary">
          <v-icon dark>chevron_left</v-icon>
        </v-btn>
      </v-flex>
      <v-spacer></v-spacer>
      <v-flex class="text-xs-right">
        <v-btn fab dark small color="primary">
          <v-icon dark>chevron_right</v-icon>
        </v-btn>
      </v-flex>
    </v-layout> -->
  </v-container>
</template>

<script>
import Card from './Card.vue'
export default {
  components: {
    Card
  }
}
</script>
