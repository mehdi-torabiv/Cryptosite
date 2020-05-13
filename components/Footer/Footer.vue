<template>
  <footer>
    <div class="container mx-auto text-justify" id="Contactus">
      <div class="footer-btm-wrapper">
        <div class="sm:block-flex md:flex justify-between">
          <div class="footersec sm:p-4 md:p-8 pl-0">
            <h2 class="text-2xl font-bold text-white">لوگو شرکت</h2>
            <p class="py-4 text-justify">
              تمام قالب های وب سایت ما همانطور که ارائه می شود ، ما هیچ تضمینی
              را ارائه نمی دهیم یا قالب های وب سایت ضمانت نامه همانطور که ارائه
              می شود ، ارائه نمی دهیم.
            </p>
          </div>
          <div class="footersec1">
            <h2 class="text-2xl font-bold text-teal-400">شرکت</h2>
            <ul class="py-2">
              <li>
                <a href>خانه</a>
              </li>
              <li>
                <a href>درباره</a>
              </li>
              <li>
                <a href>سرویس ها</a>
              </li>
              <li>
                <a href>تیم</a>
              </li>
            </ul>
          </div>
          <div class="footersec1">
            <h2 class="text-2xl font-bold text-teal-400">شرکت</h2>
            <ul class="py-2">
              <li>
                <a href>پشتیبانی</a>
              </li>
              <li>
                <a href>سیاست ها</a>
              </li>
              <li>
                <a href>چت آنلاین</a>
              </li>
              <li>
                <a href>پشتیبانی</a>
              </li>
            </ul>
          </div>
          <div class="footersec1">
            <h2 class="text-2xl font-bold text-teal-400">شرکت</h2>
            <ul class="py-2">
              <li>
                <a href>مشتری</a>
              </li>
              <li>
                <a href>شرایط وضوابط</a>
              </li>
              <li>
                <a href>پرسش هاوسوالات</a>
              </li>
              <li>
                <a href>قیمت گذاری</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="copyright mx-auto">
      <p>
        Copyright © and Designed By
        <span>NikoBit</span>
      </p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  width: 100%;
  height: 100%;
  /*  padding-top: 150px;*/
  background: url("../../assets/images/bg-img/footer-02.jpg") no-repeat 100%
    100%;
  background-size: cover;
  padding-top: 5rem;
}
.footer-btm-wrapper {
  padding-bottom: 80px;
}
.footersec > * {
  width: 75%;
}
.footersec > p {
  color: white;
}
.footersec1 {
  width: 20%;
}

.footersec1 a {
  color: white;
  font-size: 16px;
  padding: 0.5rem 0;
}
.footersec1 h2 {
  color: #00e9fe;
}
.footersec1 a:hover {
  padding-right: 0.2rem;
  transition: padding 0.3s ease-out;
}
.footersec1 li {
  margin-bottom: 0.8rem;
}
.copyright {
  border-top: 1px solid rgba(236, 237, 238, 0.192);
  width: 100%;
}
.copyright p {
  font-size: 18px;
  margin: 0;
  padding: 30px 0;
  border: none;
  line-height: 18px;
  text-align: center;
  font-weight: 300;
  color: #a4acc4;
}
</style>
