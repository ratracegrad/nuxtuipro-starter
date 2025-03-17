<template>
  <UNavigationMenu orientation="horizontal" :items="items" class="data-[orientation=vertical]:w-48" />
</template>

<script setup lang="ts">
const items = [{
  label: 'Features',
  to: '/#features'
}, {
  label: 'Pricing',
  to: '/#pricing'
}, {
  label: 'FAQ',
  to: '/#faq'
}]
</script>

<style scoped>

</style>