<template>
  <div class="flex smallPost items-center text-right">
      <div class="header">
        <img src="@/assets/images/crypto.jpg" alt="">
      </div>
      <div class="title">
          <h1>بیت کوین همواره پیشتاز</h1>
          <p>لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و </p>
          <div class="date flex justify-end pl-2">
              <p>17 آذر</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.smallPost{
    background: white;
    /* border: 1px solid rgba(0, 0, 0, 0.082); */
    padding: .5rem;
    border-radius: 5px;
    /* box-shadow: rgba(0,0,0,.15) 0 7px 7px; */
}
.smallPost:hover{
    cursor: pointer;
}
.header>img{
    width: 200px;
    height: 120px;
    border-radius: 5px;
}
.title{
    box-sizing: border-box;
    padding-right: 15px;
    display: table;
}
</style>