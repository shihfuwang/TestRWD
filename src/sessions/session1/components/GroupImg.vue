<script setup lang="ts">
import { defineProps } from 'vue';

const props = defineProps<{
  img: string
}>();
</script>

<template>
  <img
    :src="props.img"
    class="
      w-[152px] h-[200px]
      sm:w-[232px] sm:h-[306px]
    "
  />
</template>