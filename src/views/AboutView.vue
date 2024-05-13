<script setup>
import TheResume from '../components/TheResume.vue'
</script>

<template>
  <main>
    <div class="resume">
      <TheResume />
    </div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: right;
  }

  main .resume {
    max-height: 300px;
    overflow-y: scroll;
  }
}
</style>
