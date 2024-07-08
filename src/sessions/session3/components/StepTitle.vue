<script setup lang='ts'>
import { defineProps } from 'vue';
import orangeFrame from '../../../assets/images/orange-frame.png';

const props = defineProps<{
  title: string,
}>();
</script>

<template>
  <div
    :style="{ backgroundImage: `url(${orangeFrame})`, backgroundSize: 'cover', backgroundPosition: 'center' }"
    class="
      flex flex-col justify-center bg-no-repeat w-[248.571px] h-[50px]
      sm:w-[298.286px] sm:h-[60px]
      md:w-[348px] md:h-[70px]
    "
  >
    <p class="title text-[20px] sm:text-[25px] md:text-[30px]">{{props.title}}</p>
  </div>
</template>

<style scoped>
.title {
  color: #FFF;
  text-align: center;
  text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.50);
  font-family: Inter;
  font-weight: 700;
  line-height: normal;
}
</style>
