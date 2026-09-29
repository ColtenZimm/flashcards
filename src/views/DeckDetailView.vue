<template>
  <div class="deck-detail">
    <h1>{{ deck.name }}</h1>
    <p>{{ deck.description }}</p>
    <ul>
      <li v-for="card in deck.cards" :key="card.id">{{ card.front }} - {{ card.back }}</li>
    </ul>
  </div>
</template>
