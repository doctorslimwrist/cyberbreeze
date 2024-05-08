<script setup>
import TheResume from '../components/TheResume.vue'
</script>

<template>
  <main>
    <div>
      <TheResume />
    </div>
  </main>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}

#inside {
  position: fixed;
  width: 300px;
  border: 4px solid red;
  margin: -200px 100px -200px 100px;
}

#container {
  height: 100%;
  border: 4px solid greenyellow;
}
</style>
