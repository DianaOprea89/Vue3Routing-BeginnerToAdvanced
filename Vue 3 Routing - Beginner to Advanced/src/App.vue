<script setup>
import {RouterView, RouterLink } from "vue-router"
</script>
<template>
  <main>
    <div class="links">
      <RouterLink to="/" active-class="active">Home</RouterLink>
      <RouterLink to="/about" active-class="active">About</RouterLink>
    </div>
  <RouterView/>
  </main>
</template>
<style scoped>
.links {
  padding: 20px
}
.links a {
  margin: 0 5px
}
.active{
font-weight: bold;
  color: green;
}
</style>