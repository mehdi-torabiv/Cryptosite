<template>
  <div class="section s-1 overflow-hidden" 
        @click="GoToPage()" 
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-once="true">
    <div class="overflow-hidden">
        <img src="@/assets/images/crypto.jpg" class="img-hover" alt="">
    </div>
    <div class="section-text w-full">
        <div class="pr-2">
            <h1 class="font-bold">BTC سرمایه گذاری آینده</h1>
            <p class="font-16">رشد قیمت بیت کوین در ماه اخیر</p>
        </div>
        <div class="flex w-1/3 justify-between px-2">
            <p class="font-12 font-bold">18 آذر</p>
            <p class="font-12 font-bold">علی رضا منصوری</p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    methods:{
        GoToPage(){
            this.$router.push('/blog-post')
        }
    }
}
</script>

<style>

</style>