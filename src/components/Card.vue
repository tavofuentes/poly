<template>
  <v-card color="" class="blue-grey--text darken-2--text">
    <v-fab-transition>
      <v-btn
        v-show="!hidden"
        color="grey"
        fab
        dark
        small
        absolute
        bottom
        left
      >
        <v-icon>chevron_left</v-icon>
      </v-btn>
    </v-fab-transition>
    <v-fab-transition>
      <v-btn
        v-show="!hidden"
        color="grey"
        fab
        dark
        small
        absolute
        bottom
        right
      >
        <v-icon>chevron_right</v-icon>
      </v-btn>
    </v-fab-transition>
    <v-layout>
      <v-flex xs8>
        <v-card-title primary-title>
          <div>
            <div class="headline">Cerveza</div>
          </div>
        </v-card-title>
      </v-flex>
    </v-layout>
    <v-divider light></v-divider>
    <v-card-actions class="pa-3 pb-5">
      Rate this album
    </v-card-actions>
  </v-card>
</template>

