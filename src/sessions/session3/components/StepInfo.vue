<script setup>
import StepTitle from './StepTitle.vue';
</script>

<template>
 <div
   class="
      flex flex-col justify-center items-center gap-[12px] self-stretch
      sm:h-[140px] sm:gap-[18.5px] sm:shrink-0
      md:w-[500px] md:h-[167px] md:gap-[25px]
   "
>
    <StepTitle :title="'冠軍預測:第一階段'"/>
    <p
      class="
         text text-[16px] w-[300px] h-[48px] gap-[5px]
         sm:text-[20px] sm:w-[400px] sm:h-[60px] sm:gap-[8px]
         md:text-[24px] md:w-[500px] md:h-[72px] md:gap-[10px]
      "
   >
      用充值金額預測冠軍國家如預測成功可獲得儲值金額的3%
   </p>
 </div>
</template>

<style scoped>
.text{
color: #36FECD;
text-align: center;
font-family: Inter;
font-style: normal;
font-weight: 600;
line-height: 150%;
}
</style>