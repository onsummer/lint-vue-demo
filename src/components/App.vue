<template>
  <div>{{ foo }}</div>
</template>

<script setup lang="ts">
import { onMounted, ref } from 'vue'

const foo = ref(1)

onMounted(() => {
  console.log(123)
})
</script>

<style>
div {
  color: aliceblue;
}
</style>
