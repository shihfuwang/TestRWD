<script setup lang='ts'>
import GroupImg from './GroupImg.vue';
import groupInfo from '../../../assets/images/team-a.png';
import groupInfo1 from '../../../assets/images/GroupInfo.png';
import groupInfo2 from '../../../assets/images/GroupInfo1.png';
import groupInfo3 from '../../../assets/images/GroupInfo2.png';
import groupInfo4 from '../../../assets/images/GroupInfo3.png';
import groupInfo5 from '../../../assets/images/GroupInfo4.png';

</script>

<template>
  <div class="flex flex-wrap justify-center items-center w-[324px] sm:w-[496px] md:w-[736px] gap-[20px]">
    <GroupImg :src="groupInfo"/>
    <GroupImg :src="groupInfo1"/>
    <GroupImg :src="groupInfo2"/>
    <GroupImg :src="groupInfo3"/>
    <GroupImg :src="groupInfo4"/>
    <GroupImg :src="groupInfo5"/>
  </div>
</template>