<script setup lang="ts">
import { ref } from 'vue';

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <button
    class="
      px-4
      py-2
      bg-blue-500
      rounded-full
      text-base
      hover:bg-blue-600
      text-white
    "
  >
    <slot />
  </button>
</template>
