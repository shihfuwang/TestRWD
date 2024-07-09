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
  <div
    class="
      flex flex-wrap justify-center items-center w-[324px] gap-[20px]
      sm:w-[496px]
      md:w-[736px]
    "
  >
    <GroupImg :img="groupInfo"/>
    <GroupImg :img="groupInfo1"/>
    <GroupImg :img="groupInfo2"/>
    <GroupImg :img="groupInfo3"/>
    <GroupImg :img="groupInfo4"/>
    <GroupImg :img="groupInfo5"/>
  </div>
</template>