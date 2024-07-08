<script setup lang="ts">
import Title3 from './components/Tittle3.vue';
import RuleBg from './components/RuleBg.vue';
import Content from './components/Content.vue'
</script>

<template>
  <div class="flex flex-col items-center gap-[30px]">
    <Title3 />
    <RuleBg class="relative">
      <Content class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2" />
    </RuleBg>
  </div>
</template>

<style scoped>

</style>
