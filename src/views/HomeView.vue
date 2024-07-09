<script setup>
import { useCounterStore } from '@/stores/counter'

const store = useCounterStore()

</script>

<template>
  <v-btn @click="store.increment">increment</v-btn>
  Current Count: {{ store.count }}
  <v-btn @click="store.decrement">Decrement</v-btn>
</template>
<style scoped></style>