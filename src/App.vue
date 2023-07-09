<script setup>
import { ref, onMounted } from 'vue'

const pElementRef = ref(null)

onMounted(() => {
  pElementRef.value.textContent = 'World'
})
</script>

<template>
  <p ref="pElementRef">hello</p>
</template>
