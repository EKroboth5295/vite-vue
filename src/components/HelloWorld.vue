<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <p>
      Hello World!
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.card {
  height: 4em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
</style>
