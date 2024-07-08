<script setup lang="ts">
import BearBannerRight from './BearBannerRight.vue';
import BearBannerLeft from './BearBannerLeft.vue';
import BearFootBall from './BearFootball.vue';
import BearBannerGroup from './BearBannerGroup.vue';
</script>

<template>
  <div
    class="
      flex flex-col items-center gap-[30px]
    "
  >
    <BearBannerRight class="md:hidden"/>
    <BearBannerLeft class="md:hidden"/>
    <BearFootBall class="md:hidden sm:h-[458px]"/>
    <BearBannerGroup class="hidden md:block" />
  </div>
</template>

<style scoped>

</style>


<style scoped>

</style>
