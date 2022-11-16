<script setup>
import { ref } from 'vue';
import HeadingMessage from '@/components/HeadingMessage.vue';
const count = ref(0);
</script>

<template>
  <div class="grid min-h-screen place-content-center bg-gradient-to-r from-sky-400 to-blue-500 text-center">
    <div class="text-center">
      <div class="mb-6 text-[130px] font-bold leading-none text-white">{{ count }}</div>
      <button
        class="mb-6 select-none rounded-md border-0 bg-orange-600 py-4 px-8 text-xl text-orange-50 shadow-lg hover:bg-orange-700"
        type="button"
        @click="count++"
      >
        Increment The Count
      </button>
    </div>
    <HeadingMessage msg="Placeholder Page" />
  </div>
</template>
