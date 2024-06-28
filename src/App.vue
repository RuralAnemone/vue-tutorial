<script setup>
import { reactive, ref } from 'vue'

const message = ref("hello world");
console.log(message);
// message.value = "hello mars";

const counter = reactive({
  count: 0
});

counter.count++;

</script>

<template>
  <h1>{{ message }}</h1>
  <p>count is {{ counter.count }}</p>
</template>