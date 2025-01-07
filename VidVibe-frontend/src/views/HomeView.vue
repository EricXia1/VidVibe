<script setup>
import { ref } from 'vue';

const urlInput = ref('');
</script>

<template>
  <main class="bg-gradient-to-r from-purple-400 via-pink-500 to-red-500 min-h-screen flex flex-col items-center justify-center">
    <h1 class="text-white text-4xl font-bold mb-4">VidVibe</h1>
    <input v-model="urlInput" placeholder="Paste YouTube URL here!" class="p-2 rounded" />
  </main>
</template>

<style scoped>
main {
  padding: 20px;
}
</style>