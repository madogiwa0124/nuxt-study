<template>
  <div>
    <span>{{ message }}</span>
    <span>{{ runtimeConfig.apiSecret }}</span>
  </div>
</template>
<script setup>
const runtimeConfig = useRuntimeConfig();
const message = ref("Hello!!");
</script>
