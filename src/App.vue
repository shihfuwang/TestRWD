<script setup lang="ts">
import Session1 from './sessions/session1/Session1.vue';
import Session2 from './sessions/session2/Session2.vue';
import Session3 from './sessions/session3/Sesson3.vue';
import bg from '../src/assets/images/image 1.png';
</script>

<template>
  <div
    class="
      flex flex-col justify-center items-center overflow-x-clip
      sm:gap-[75px] md:gap-[100px]
    "
    :style="{ backgroundImage: `url(${bg})`, backgroundAttachment: 'fixed', backgroundSize: 'cover', backgroundPosition: 'center' }"
  >
    <Session1/>
    <Session2 />
    <Session3 />
  </div>
</template>

<style scoped>

</style>
