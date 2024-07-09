<script setup lang="ts">
import bearBanner from './BearBanner.vue';
import FootballImg from './FootBallImg.vue';
</script>

<template>
  <div
    class="
      flex justify-center items-center w-[800px] h-[428px] relative
    "
    >
    <FootballImg class="absolute md:left-[314px] md:bottom-0"/>
    <bearBanner />
  </div>
</template>

<style scoped>

</style>
