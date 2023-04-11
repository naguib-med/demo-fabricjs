<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
   <v-app>
      <v-app-bar app color="red">
         <v-toolbar-title>Poster Editor</v-toolbar-title>
         <v-spacer></v-spacer>
         <v-btn color="dark" href="https://github.com/naguib-med/demo-fabricjs" target="_blank">GitHub</v-btn>
      </v-app-bar>
      <v-main>
          <RouterView/>
      </v-main>
    </v-app>
</template>

