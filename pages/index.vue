<template>
hey index master
  <NuxtLink to="/test">TEst</NuxtLink><br>
  <a href="http://ttt.localhost:3000/dashboard/">go to sub</a>
</template>

<script setup>
useHead({
  link: [
    { rel: 'icon', type: 'image/x-icon', href: '/favicon.png' },
  ]
})
</script>

<style scoped>

</style>