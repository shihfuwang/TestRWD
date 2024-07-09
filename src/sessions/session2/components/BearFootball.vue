<script setup lang="ts">
import BearImg from './BearImg.vue';
import FootBallImg from './FootBallImg.vue';
</script>

<template>
  <div
    class="
      flex flex-col items-start relative w-[249px] h-[369px]
      sm:w-[308px] sm:h-[458px]
    "
  >
    <FootBallImg
      class="
        absolute right-[38.97px] bottom-0
        sm:left-[49px] sm:bottom-[0.265px]
      "/>
    <BearImg class="absolute right-[4px] sm:right-0 sm:left-[5px]"/>
  </div>
</template>

<style scoped>

</style>
