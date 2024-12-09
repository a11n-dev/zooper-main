<template>
  <main class="min-h-screen">
    <AppHeader class="mb-8" title="Impressum" :description="description" />
  </main>
</template>

<script setup>
const description =
  "This page contains information about the website owner, the website itself, and the legal information required by German law.";

useSeoMeta({
  title: "Impressum | ",
  description,
});
</script>
