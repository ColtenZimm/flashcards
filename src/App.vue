<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">Decks</RouterLink>
    <RouterLink to="/stats">Stats</RouterLink>
  </nav>
  <RouterView />
</template>
