<template>
  <UPageSection id="hero">
    <UPageHero
      title="Nuxt UI Pro - Starter"
      description="Nuxt UI Pro is a collection of premium components built on top of Nuxt UI to create beautiful & responsive applications in minutes."
      headline="New release"
      orientation="horizontal"
      :links="[{
        label: 'Get started',
        to: 'https://ui.nuxt.com/getting-started/installation/pro/nuxt',
        target: '_blank',
        trailingIcon: 'i-lucide-arrow-right',
        size: 'xl'
      }, {
        label: 'Use this template',
        to: 'https://github.com/nuxt-ui-pro/starter',
        target: '_blank',
        icon: 'i-simple-icons-github',
        size: 'xl',
        color: 'neutral',
        variant: 'subtle'
      }]"
    >
      
      <img
        src="https://ui.nuxt.com/templates/dashboard1.png"
        alt="App screenshot"
        class="rounded-lg shadow-2xl ring ring-(--ui-border)"
      >
    </UPageHero>
  </UPageSection>
</template>

