<template>
  <h2>Hello from generic subdomain</h2>
  <NuxtLink to="/dashboard/test"> go to test</NuxtLink><br>
  <NuxtLink to="/dashboard/mpoumpoukos"> go to mpoumpoukos</NuxtLink>
  <Footer/>
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