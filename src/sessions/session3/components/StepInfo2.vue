<script setup>
import StepTitle from './StepTitle.vue';
</script>

<template>
 <div
  class="
    flex flex-col items-center gap-[12px] self-stretch
    sm:gap-[18.5px] sm:w-[399px] sm:shrink-0
    md:gap-[25px] md:w-[500px] "
  >
    <StepTitle :title="'冠軍集氣-第二階段'"/>
    <div class="flex flex-col gap-[5px] sm:gap-[8px] md:gap-[10px]">
    <p
      class="
        text text-[16px] w-[300px] h-[48px]
        sm:text-[20px] sm:w-[399px] sm:h-[60px]
        md:text-[24px] md:w-[500px] md:h-[72px]
      "
    >
      下注自身預測的國家，如循環賽中獲勝可在獲得下注金額的5%
    </p>
    <span
      class="
        example text-[16px]
        sm:text-[20px]
        md:text-[24px]
      "
    >
      舉例➜熊達在第一階段充值10萬元並且預測德國隊獲勝
      <p  class="example">
      ➜比賽開始後有德國隊賽事的場次都下注德國隊獲勝可在額外獲得獲利金額的5%<br>
      ➜如德國隊最後為冠軍可再獲得第一階段預測充值金額的3%
      </p>
    </span>
  </div>
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

.example{
  color: #FFF;
  text-align: center;
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  line-height: 150%;
}
</style>