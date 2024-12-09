<template>
  <main class="min-h-screen">
    <AppHeader class="mb-12" title="Contact" :description="description" />
  </main>
</template>

<script setup>
const description =
  "I'm always open to new opportunities, collaborations, or just a friendly chat. Feel free to reach out to me via email or any of the social media platforms listed below.";

useSeoMeta({
  title: "Contact | ",
  description,
});
</script>
