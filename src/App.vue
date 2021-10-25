<script setup lang="ts">
useHead({
  title: 'Vitesse-Lite-With-ssg',
  meta: [
    { name: 'description', content: 'Opinionated Vite Starter Template' },
  ],
})
</script>

<template>
  <main class="px-4 py-10 text-center text-gray-700 dark:text-gray-200">
    <router-view />
    <Footer />
  </main>
</template>
