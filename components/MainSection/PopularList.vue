<template>
  <div class="w-full">
     <PopularListItem/>
     <PopularListItem/>
     <PopularListItem/>
     <PopularListItem/>
     <Archive />
  </div>    
</template>

<script>
import PSmallCard from './MainComponent/PSmallCard';
import PopularListItem from './PopularListItem';
import Archive from './Archive';
export default {
    components:{
        PSmallCard,
        PopularListItem:PopularListItem,
        Archive
    }
}
</script>

<style>

</style>