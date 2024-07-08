<script setup lang='ts'>
import bg from '../../../assets/images/bg-rule.png';
</script>

<template>
  <div
    :style="{backgroundImage: `url(${bg})`, backgroundPosition: 'center', backgroundSize: 'contain'}"
    class="
      w-[375px] h-[498px] bg-no-repeat
      sm:w-[521px] sm:h-[692px]
      md:w-[681px] md:h-[905px]
    "
  >
    <slot></slot>
  </div>
</template>

