<template>
  <div class="pt-8 newPost">
    <h1 class="font-bold text-right pb-4">اخبار پربیننده سایت</h1>
    <hr>
    <div class="w-2/3 header pt-6 ">
            <div>
                <img src="@/assets/images/crypto.jpg" alt="">
            </div>  
            <div class="title w-full text-right">
                <h1>بیت کوین در راه صعود</h1>
                <div class="flex w-1/5 justify-between">
                    <p>آذر کریمی</p>
                    <p>17 آذر</p>
                </div>
            </div>
            
    </div>
    <div>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.newPost{
}
.header{
    height: 350px;
    overflow: hidden;
    position: relative;
}
.title{
    position: absolute;
    bottom: 5px;
    color: white;
}
.header >img{
    border-radius: 10px;
}
/* .header >img{
    width: 100%;
    height: 400px;
} */
</style>