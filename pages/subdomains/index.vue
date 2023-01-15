<template>
  <h2>Hello from generic subdomain</h2>
  <NuxtLink to="/subdomains/test"> go to test</NuxtLink>
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