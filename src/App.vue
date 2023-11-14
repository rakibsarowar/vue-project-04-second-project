<script setup>
  import { ref } from "vue";
  const product = ref('socks')
</script>

<template>
  <div class="nav-bar"></div>
  <div>
    <h1>{{ product }}</h1>
  </div>
</template>


