<script setup>
defineProps({
  msg: {
    type: String,
    default: 'Sample Component',
  },
});
</script>

<template>
  <h1 class="text-3xl font-light text-white">{{ msg }}</h1>
</template>
