<template>
  <div class="flex flex-col-reverse md:flex-row" 
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-once="true">
    <div class="md:w-9/12 pt-8">
      <PopularPost/>
      
    </div>
    <!-- <div class="md:w-4/12 pt-8">
        <vs-tabs>
            <vs-tab class="w-full" label="مطالب اخیر">
                <div class="con-tab-ejemplo">
                    <PopularList/>
                </div>
            </vs-tab>
            <vs-tab class="w-full" label="مطالب محبوب">
                <div class="con-tab-ejemplo">
                    <PopularList/>
                </div>
            </vs-tab>
        </vs-tabs>
    </div> -->
  </div>
</template>

<script>
import PopularPost from './MainComponent/PopularPost';
import PopularList from './PopularList';
export default {
    PopularPost,
    PopularList
}
</script>

<style>

</style>