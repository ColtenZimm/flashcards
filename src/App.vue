<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/decks/:id">Deck</RouterLink>
    <RouterLink to="/study/:id">Study</RouterLink>
    <RouterLink to="/stats">Stats</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterView />
  </nav>
</template>
