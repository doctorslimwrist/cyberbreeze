<script setup>
import ListItem from './ListItem.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
  <ListItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>(612) 403-5240</template>
  </ListItem>
  <ListItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>abbyschneider612@gmail.com</template>
  </ListItem>
</template>
