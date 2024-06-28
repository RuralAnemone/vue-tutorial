<script setup>
import { ref } from 'vue'

const text = ref('')
setInterval(() => {
  text.value += "h"
}, 1000)
</script>

<template>
  <input v-model="text" placeholder="Type here">
  <p>{{ text }}</p>
</template>