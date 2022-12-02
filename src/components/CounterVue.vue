<script setup>
import { ref } from "vue";

const count = ref(0);
</script>
<template>
  <h1>Vue Counter</h1>
  <div>{{ count }}</div>
  <div>
    <button @click="count++">increment</button>
    <button @click="count--">decrement</button>
  </div>
</template>
