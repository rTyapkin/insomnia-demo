<template>
  <v-app id="app">
    <INavigationBar />
    <v-main class="main fill-height">
      <v-container>
        <INavigationDrawer />
        <MainWindow />
      </v-container>
    </v-main>
  </v-app>
</template>

<script lang="ts" setup>
import INavigationBar from "@/components/INavigationBar.vue";
import INavigationDrawer from "@/components/INavigationDrawer.vue";
</script>
