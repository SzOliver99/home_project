<script setup>
  import HomePage from "./components/HomePage.vue";
  import Navbar from "./components/Navbar.vue";
</script>

<template>
  <Navbar/>
  <main class="py-5">
    <RouterView/>
  </main>
  <footer class="flex flex-col bg-blue-950 py-5 text-white items-center">
    <p class="pb-3 text-sm">&#169 2024 Your Company. All rights reserved.</p>
  </footer>
</template>