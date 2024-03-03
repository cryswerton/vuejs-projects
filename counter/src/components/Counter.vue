<template>
    <button @click="count++">
    Count is: {{ count }}
  </button>
</template>

<script setup>
import { ref } from 'vue'

let count = ref(0)

</script>

<style scoped>
    
</style>