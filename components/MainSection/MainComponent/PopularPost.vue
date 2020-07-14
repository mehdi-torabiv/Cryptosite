<template>
  <div class="">
      <h1 class="font-bold text-right pb-4">اخبار سایت</h1>
      <!-- <vs-divider/> -->
    <div class="w-full pt-6 block md:flex justify-between">
      <PMainCard/>
      <div class="md:w-2/3 pr-2">
        <PSmallCard/>
        <PSmallCard class="mt-2"/>
        <PSmallCard class="mt-2"/>
        <PSmallCard class="mt-2"/>
      </div>
      <!-- <div class="w-1/3"></div> -->
    </div>
    
  </div>
</template>

<script>
import PMainCard from './PMainCard';
import PSmallCard from './PSmallCard';

export default {
  components:{
    PMainCard,
    PSmallCard
  }
}
</script>

<style>

</style>