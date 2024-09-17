<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavigationBarView from './views/NavigationBarView.vue'
</script>

<template>
  <NavigationBarView />
  <RouterView />
</template>

<style scoped></style>
