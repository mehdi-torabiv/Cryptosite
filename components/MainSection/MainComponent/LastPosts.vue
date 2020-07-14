<template>
  <div class="w-full md:flex">
      <div class="pt-8 flex flex-row flex-wrap md:w-9/12">
        <h1 class="font-bold text-right pb-4">اخبار پربیننده سایت</h1>
        <hr>
        <div class="pt-8 md:w-full flex flex-row flex-wrap">
          <PMainCard class="pl-2"/>
          <PMainCard class="pr-2"/>
          <PMainCard class="pr-2"/>
          <PMainCard class="pr-2"/>
        </div>
      </div>
      <div class="pt-8 flex flex-col  flex-wrap md:w-4/12">
       <div class="w-full">
         <h2 class="pb-2 text-right">مطالب پرمخاطب سایت</h2>
         <hr class="pb-2">
         <PopularItem/>
         <PopularItem/>
         <PopularItem/>
         <PopularItem/>
       </div>
       <div>
         <Tags/>
       </div>
      </div>
  </div>
</template>

<script>
import PMainCard from './PMainCard';
import PopularListItem from '../PopularListItem';
import Tags from './Tags';
export default {
    components:{
        PMainCard,
        PopularItem:PopularListItem,
        Tags
    }
}
</script>

<style>

</style>