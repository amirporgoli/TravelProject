<template :style="{background: $vuetify.theme.themes.light.colors.primary}">
  <v-app >
    <default-bar />

    <default-view />
  </v-app>
</template>

<script setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
</script>
