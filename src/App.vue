<script setup lang="ts">
useHead({
  title: 'Vitesse-Lite-With-ssg',
  meta: [
    { name: 'description', content: 'Opinionated Vite Starter Template' },
  ],
})
</script>

<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
    <router-view />
    <Footer />
  </main>
</template>
