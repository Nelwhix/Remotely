<script setup lang="ts">
import Navigation from "./components/Navigation.vue";
import Overlay from "./components/Overlay.vue";

</script>

<template>
  <Navigation />
  <Overlay class="hidden" />
  <RouterView />
</template>
