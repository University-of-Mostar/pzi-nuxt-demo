<script setup lang="ts">

</script>

<template>
  <v-app-bar
      fixed
      app
      height="100"
  >
    <v-toolbar-title>
      <img class="tw-max-h-[80px]" src="/img/sumit-logo.svg"/>
    </v-toolbar-title>
    <v-spacer/>
    <v-btn
        variant="outlined"
        class="text-none"
        to="/login"
    >
      <v-icon class="tw-mr-1" small>mdi-account-outline</v-icon>
      Administracija
    </v-btn>
  </v-app-bar>
</template>

<style scoped>

</style>