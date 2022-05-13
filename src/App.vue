<template>
  <NavBar />
  <main class="px-7 py-10">
    <router-view />
    <Footer />
  </main>
</template>

<script setup lang="ts">
useHead({
  meta: [
    { property: "og:title", content: "Arun Govil" },
    {
      property: "og:image",
      content: "https://arungovil.github.io/avatar.webp",
    },
    { name: "description", content: "Arun Govil's Portfolio" },
  ],
});
</script>
