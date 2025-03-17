<template>
  <USeparator icon="i-heroicons:rocket-launch" />
  <UFooter>
    <template #left>
      <p class="text-sm text-(--ui-text-muted)">
        Copyright © {{ new Date().getFullYear() }}
      </p>
    </template>

    <template #right>
      <UButton
        to="https://github.com/nuxt-ui-pro/starter"
        target="_blank"
        icon="i-simple-icons-github"
        aria-label="GitHub"
        color="neutral"
        variant="ghost"
      />
    </template>
    </UFooter>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>