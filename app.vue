<script setup lang="ts">
useHead({
  titleTemplate: '%s - VulkanHub',
})
</script>

<template>
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
  <ClientOnly>
    <DocSearch />
  </ClientOnly>
</template>

<style>
body {
  overflow-x: hidden;
  overflow-wrap: break-word;
}
</style>
