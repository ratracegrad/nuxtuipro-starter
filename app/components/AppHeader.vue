<template>
  <UHeader>
    <template #left>
      <NuxtLink to="/">
        <AppName class="w-auto h-6 shrink-0" />
      </NuxtLink>
    </template>

    <template #default>
      <AppMenu />
    </template>

    <template #right>
      <UColorModeButton />

      <UButton
        to="https://github.com/nuxt-ui-pro/starter"
        target="_blank"
        icon="i-simple-icons-github"
        aria-label="GitHub"
        color="neutral"
        variant="ghost"
      />
    </template>
  </UHeader>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>