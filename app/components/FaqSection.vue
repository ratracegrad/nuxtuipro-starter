<script setup lang="ts">
const items = ref([
  {
    label: 'What are the main considerations when upgrading to Nuxt UI v3?',
    icon: 'i-lucide-circle-help',
    content: 'The transition to v3 involves significant changes, including new component structures, updated theming approaches, and revised TypeScript definitions. We recommend a careful, incremental upgrade process, starting with thorough testing in a development environment.'
  },
  {
    label: 'Is Nuxt UI v3 compatible with standalone Vue projects?',
    icon: 'i-lucide-circle-help',
    content: 'Nuxt UI is now compatible with Vue! You can follow the installation guide to get started.'
  },
  {
    label: 'What about Nuxt UI Pro?',
    icon: 'i-lucide-circle-help',
    content: 'We also rebuilt Nuxt UI Pro from scratch and released a v3.0.0-alpha.x package but it only contains the components to build this documentation yet. This will be a free update, so the license you buy now will be valid for v3. We are actively working to finish the rewrite of all Nuxt UI Pro components.'
  }
])
</script>

<template>
  <UPageSection 
    title="Frequently Asked Questions"
    description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, quos."
  >
    <UPageAccordion :items="items" />
  </UPageSection>
</template>
