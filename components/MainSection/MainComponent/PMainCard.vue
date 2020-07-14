<template>
  <div class="w-1/3 post">
      <div class="header overflow-hidden">
          <img src="@/assets/images/crypto.jpg" class="overflow-hidden" alt="">
      </div>
      <div class="body text-right flex flex-col ">
          <div class="title block">
              <h1>بیت کوین همواره پیشتاز</h1>
              <div class="flex justify-between">
                  <p>سامیار رضایی</p>
                  <p>17 آذر</p>
              </div>
              <div>
                <p class="text-justify text-right">
                    لورم ایپسوم یا طرح‌نما (به انگلیسی: Lorem ipsum) به متنی آزمایشی و بی‌معنی در صنعت چاپ، صفحه‌آرایی و طراحی گرافیک گفته می‌شود. طراح گرافیک از این متن به عنوان عنصری از ترکیب بندی برای پر کردن صفحه و ارایه اولیه شکل ظاهری و کلی طرح سفارش گرفته شده استفاده می نماید، تا از نظر گرافیکی نشانگر چگونگی نوع و اندازه فونت و ظاهر متن باشد. 
                </p>
              </div>
          </div>
          <div class="mt-2 w-full mx-auto flex justify-end">
              <div class="ml-4">
                <button>بیشتر...</button>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.post{
    position: relative;
    height: 400px;
    width: 400px;
    box-sizing: border-box;
    margin-bottom: 14rem;
    cursor: pointer;
}
.header{
    position: relative;
}
.header>img{
    border-radius: 10px;
}
.header>img:hover{
    border-radius: 10px;
    transform: scale(1.5);
    transition: .5s;
    overflow: hidden;
}
.body{
    background: white;
    border-radius: 10px;
    box-shadow: rgba(0,0,0,.15) 0 7px 7px;
    /* margin-bottom: 15px; */
    position: relative;
    margin-left: 10px;
    z-index: 500;
    margin-top: -45px;
    margin-right: 12px;
    box-sizing: border-box;
    padding: 1rem;
    /* width:400px; */
}
.body > .title{
    padding: .5rem .4rem;
}
button{
    background: white;
    border: 1px rgb(179, 179, 179) solid;
    padding:  8px 20px;
    
}
button:hover{
    background: rgb(179, 179, 179);
    transition: .5s ease;
    color: white;
    border: 1px rgb(179, 179, 179) solid;
}
h1{
    font-size: 18px;
    font-weight: bold;
}
p{
    color: grey;
}
</style>