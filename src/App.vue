<template>
  
<main class="bg-slate-100">

  <nav>
    <RouterLink to="#/">Home</RouterLink>
    <RouterLink href="#/features">Features</RouterLink>
    <RouterLink href="#/pricing">Pricing</RouterLink>
    <RouterLink href="#/contact">Contact</RouterLink>
  </nav>

  <RouterView />

</main>

</template>

<script lang="ts">
import { RouterLink, RouterView } from 'vue-router';



</script>

<style scoped>

</style>