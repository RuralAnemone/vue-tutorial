<script setup>
import { ref } from 'vue'

const message = ref("hello world")
console.log(message)
// message.value = "hello mars"
</script>

<template>
  <h1>{{ message }}</h1>
</template>