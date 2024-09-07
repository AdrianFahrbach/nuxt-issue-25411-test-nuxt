<template>
  <div>
    <h1>{{ router.fullPath }}</h1>
  </div>
</template>

<script setup lang="ts">
const router = useRoute();
</script>
