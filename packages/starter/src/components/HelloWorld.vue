<!-- eslint-disable no-console -->
<script setup lang="ts">
defineProps<{ msg: string }>()
const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>{{ count }}</p>
</template>
