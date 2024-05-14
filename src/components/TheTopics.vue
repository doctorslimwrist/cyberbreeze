<script setup>
import ListItem from './ListItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
</script>

<template>
  <ListItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Nature grows by removal.</template>
    Resources are limited. Careful balancing of energy requires paying attention to where efforts
    can be pruned.
  </ListItem>
  <ListItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Insights are a public good.</template>
    Building in plain sight helps me treat my work as public service.
  </ListItem>
  <ListItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Forests grow slowly.</template>
    Nature's deepest beauty developed without the pressure of deadlines and KPIs.
  </ListItem>
</template>
