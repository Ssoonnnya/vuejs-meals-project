<template>
  <div class="bg-gray-100 h-full">
    <NavBar></NavBar>
    <main>
      <router-view> </router-view>
    </main>
  </div>
</template>

<script setup>

import NavBar from "./NavBar.vue";
</script>

<style scoped>

</style>