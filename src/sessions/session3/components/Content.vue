<script setup lang="ts">
import StepInfo from './StepInfo.vue';
import StepInfo2 from './StepInfo2.vue';
import LinkButton from './LinkButton.vue'
</script>

<template>
   <div
    class="
      flex flex-col items-center gap-[10px] w-[300px] h-[428px] absolute
      sm:w-[399px] sm:h-[566px] sm:gap-[28px]
      md:w-[500px] md:h-[685px] md:gap-[35px]
    "
  >
    <StepInfo />
    <StepInfo2 />
    <LinkButton/>
  </div>
</template>

<style scoped>

</style>

