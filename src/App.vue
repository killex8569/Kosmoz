<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="min-h-screen flex flex-col items-center justify-center bg-gray-50 p-8">
    <!-- Logos existants -->
    <div class="flex space-x-6 mb-8">
      <a href="https://vite.dev" target="_blank">
        <img src="/vite.svg" class="logo" alt="Vite logo" />
      </a>
      <a href="https://vuejs.org/" target="_blank">
        <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
      </a>
    </div>

    <!-- HelloWorld existant -->
    <HelloWorld msg="Vite + Vue" />

    <!-- Test Tailwind CSS -->
    <div class="mt-12 p-6 bg-blue-200 rounded-lg shadow-lg text-center">
      <h1 class="text-4xl font-bold text-red-600 underline">
        Test Tailwind CSS
      </h1>
      <p class="mt-4 text-gray-700">
        Si tu vois ce style coloré et arrondi, Tailwind fonctionne.
      </p>
      <button class="mt-6 px-4 py-2 bg-green-500 text-white font-semibold rounded hover:bg-green-600 transition">
        Bouton Tailwind
      </button>
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
