<template>
  <h2>hello from tenant mpoumpoukos</h2>
  <NuxtLink to="/dashboard/test">test</NuxtLink><br>
  <NuxtLink to="/dashboard/">index</NuxtLink>
  <Footer/>
</template>

<script>
import Footer from "~/components/Footer.vue";

export default {
  name: "mpoumpoukos",
  components: {Footer}
}
</script>

<style scoped>

</style>