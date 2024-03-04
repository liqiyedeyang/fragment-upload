<template>
  <input type="file" @change="handleUploadChange" />
</template>

<script setup lang="ts">
const handleUploadChange = (e: Event) => {
  console.log(e.target.file);
};
</script>

<style scoped></style>
