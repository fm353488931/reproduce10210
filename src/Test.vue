<template>
  <div v-for="(item, index) in items" :key="index" ref="colRef">colRef</div>
</template>

<script setup>
import { ref, onMounted } from 'vue'
const colRef = ref([])

const items = ref([])

items.value = [{}, {}] 

// setTimeout(() => {
//   items.value = [{}, {}]
// }, 300)

console.log('1111') //change it and look console
</script>
