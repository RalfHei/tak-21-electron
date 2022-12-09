<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="flex flex-col items-center justify-center py-4 border-b border-pink-200 shadow-xs bg-gradient-to-r from-pink-500 to-yellow-200">
        <RouterLink
          class="text-2xl font-medium tracking-widest text-white"
          to="/"
        >
          Home
        </RouterLink>
        <RouterLink
          class="text-2xl font-medium tracking-widest text-white"
          to="/about"
        >
          About
        </RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 60px auto;
  max-width: 700px;
}

fieldset {
  margin: 2rem;
  padding: 1rem;
}
</style>
