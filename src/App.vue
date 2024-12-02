<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/portfolio">Portfolio</RouterLink>
      </nav>
  </header>
  <RouterView />
</template>

