<template>
  <div class="news container mx-auto text-justify">
    <div class="title-wrapepr">
      <div class="news-title p-8">
        <div class="sub-title">
          <h2 data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">اخبار سایت</h2>
          <p data-aos="fade-up" data-aos-duration="750" data-aos-ease="ease-in">
            دستیار NRM مصنوعی مبتنی بر شبکه عصبی ، فوراً استفاده از داده های
            کاربر را تجزیه و تحلیل می کند....
          </p>
        </div>
        <a
          data-aos="fade-up"
          data-aos-duration="750"
          data-aos-ease="ease-in"
          href="#"
          class="moreNews"
        >بیشتر...</a>
      </div>
    </div>
    <div
      class="single-blog-wrapper inline-flex"
      data-aos="fade-up"
      data-aos-duration="1200"
      data-aos-ease="ease-in"
    >
      <div class="sm:block-flex p-8 md:inline-flex">
        <div class="single-blog mt-0 md:pl-5">
          <h3>
            <a href="#">چگونه میتوانم از سایت خرید کنم؟</a>
          </h3>
          <div class="post-date flex justify-between">
            <span class="date">15 مهر 1399</span>
            <span class="time">3 دقیقه</span>
          </div>
          <p>
            هوش مصنوعی مبتنی بر شبکه های عصبی ، ساخته شده با استفاده از جدیدترین
            الگوریتم های یادگیری خود ، مقایسه تجزیه و تحلیل نورونهایی که در آنها
            اصلاح خواهند شد ، براساس تاریخچه
          </p>
          <a class="atag" href="#">بیشتر...</a>
        </div>
        <div class="single-blog md:pl-5">
          <h3>
            <a class="aintro" href="#">لیست تبادلات اخیر</a>
          </h3>
          <div class="post-date flex justify-between">
            <span class="date">15 مهر 1399</span>
            <span class="time">3 دقیقه</span>
          </div>
          <p>
            هوش مصنوعی مبتنی بر شبکه های عصبی ، ساخته شده با استفاده از جدیدترین
            الگوریتم های یادگیری خود ، مقایسه تجزیه و تحلیل نورونهایی که در آنها
            اصلاح خواهند شد ، براساس تاریخچه
          </p>
          <a class="atag" href="#">بیشتر...</a>
        </div>
        <div class="single-blog md:pl-5">
          <h3>
            <a href="#">اخبار سایت</a>
          </h3>
          <div class="post-date flex justify-between">
            <span class="date">15 مهر 1399</span>
            <span class="time">3 دقیقه</span>
          </div>
          <p>
            هوش مصنوعی مبتنی بر شبکه های عصبی ، ساخته شده با استفاده از جدیدترین
            الگوریتم های یادگیری خود ، مقایسه تجزیه و تحلیل نورونهایی که در آنها
            اصلاح خواهند شد ، براساس تاریخچه
          </p>
          <a class="atag" href="#">بیشتر...</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.news {
  padding: 0px 0 150px;
}
.news .title-wrapepr {
  margin-bottom: 60px;
  margin-left: 0;
  position: relative;
}
.news .title-wrapepr:before {
  background: url("../../../assets/images/shape/news-shape-01.png") no-repeat
    50% 50%;
  position: absolute;
  right: 20%;
  top: -75%;
  content: "";
  height: 222px;
  width: 215px;
}
.news .title-wrapepr:after {
  background: url("../../../assets/images/shape/news-shape-02.png") no-repeat
    50% 50%;
  position: absolute;
  right: 40%;
  top: 20%;
  content: "";
  height: 181px;
  width: 178px;
}
.news .title-wrapepr .news-title {
  display: flex;
  justify-content: space-between;
}
.news .title-wrapepr .news-title .sub-title h2 {
  font-size: 36px;
  font-weight: 600;
  color: #19233b;
}
.news .title-wrapepr .news-title .sub-title p {
  color: #7a839e;
  line-height: 26px;
  font-weight: 300;
  padding-top: 20px;
  text-align: right;
  max-width: 300px;
  margin: 0;
}
.news .title-wrapepr .news-title .moreNews {
  padding: 0 21px;
  height: 36px;
  background: #562ad8;
  font-size: 16px;
  font-weight: 500;
  color: #ffffff;
  line-height: 36px;
  border-radius: 50px;
}
.news .title-wrapepr .news-title .moreNews:hover {
  background: #00e9fe;
  color: #ffffff;
  transition: ease-in-out 0.3s;
  outline: none;
  font-weight: bold;
}

.news .title-wrapepr .news-title .single-blog-wrapper {
  padding-left: 120px;
  position: relative;
}
.news .title-wrapepr .news-title .single-blog-wrapper:before {
  position: absolute;
  left: 50px;
  top: 0;
  content: "";
  border-right-style: dotted;
  opacity: 0.2;
  height: 100%;
}
.news .title-wrapepr .news-title .single-blog-wrapper:last-child:before {
  display: none;
}

.news .single-blog-wrapper .single-blog h3 a {
  font-size: 24px;
  color: #19233b !important;
  font-weight: 500;
}
.news .single-blog-wrapper .single-blog .post-date {
  padding: 30px 0;
}
.news .single-blog-wrapper .single-blog .post-date span {
  color: #7a839e !important;
  font-size: 16px;
  font-weight: 500;
}
.news .single-blog-wrapper .single-blog p {
  padding-bottom: 25px !important;
  font-weight: 300;
  margin: 0;
}
.news .single-blog-wrapper .atag {
  color: #562ad8 !important;
  font-weight: 600;
  font-size: 22px;
  float: left;
}
</style>
