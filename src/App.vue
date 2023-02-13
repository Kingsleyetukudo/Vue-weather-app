<template>
  <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
    <SiteNav />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from "vue-router";
import SiteNav from "./components/SiteNavigation.vue";
</script>

<style lang="scss" scoped></style>
