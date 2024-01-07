<script setup lang="ts">
import TheQuiz from '../components/TheQuiz.vue'
</script>

<template>
  <main class="quiz">
    <TheQuiz />
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .quiz {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>