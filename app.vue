<script setup>
import '@unocss/reset/tailwind.css'
</script>

<template>
  <div>
    <slot />
  </div>
</template>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
.dark {
  color-scheme: dark;
}
</style>
