<template>
  <div class="flex h-screen">
    <p class="underline text-2xl font-bold m-auto">{{ salam }}</p>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const salam = ref('Halu Dunia')
</script>