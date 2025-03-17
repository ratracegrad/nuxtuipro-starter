<template>
  <UPageSection>
      <UPageCTA
        title="Start with Nuxt UI Pro today!"
        description="Nuxt UI Pro is free in development, but you need a license to use it in production."
        variant="subtle"
        :links="[{
          label: 'Buy now',
          to: 'https://ui.nuxt.com/pro/purchase',
          target: '_blank',
          icon: 'i-lucide-shopping-cart',
          color: 'neutral'
        }, {
          label: 'License',
          to: 'https://ui.nuxt.com/getting-started/license',
          target: '_blank',
          trailingIcon: 'i-lucide-circle-help',
          color: 'neutral',
          variant: 'subtle'
        }]"
      />
    </UPageSection>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>