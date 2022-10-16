<template>
  <NuxtLayout>
    <MyFirstComponent />
    <NuxtWelcome />
    <ContentDoc />
    <NuxtPage />
  </NuxtLayout>
</template>
<script setup>
const res = await $fetch("/api/hello");
console.log(res.api);
</script>
