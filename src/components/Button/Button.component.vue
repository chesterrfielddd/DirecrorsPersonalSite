<script setup lang="ts">
import { ref } from 'vue'
const count = ref(0)

function increment() {
  count.value++
}
</script>

<template>
  <button type="button" @click="increment">count is: {{ count }}</button>
</template>