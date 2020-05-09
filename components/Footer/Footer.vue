<template>
  <footer>
    <div class="container mx-auto" id="Contactus">
      <div class="footer-btm-wrapper">
        <div class="sm:block-flex md:flex justify-between">
          <div class="footersec">
            <h2 class="text-2xl font-bold text-white">لوگو شرکت</h2>
            <p class="mt-8">
              تمام قالب های وب سایت ما همانطور که ارائه می شود ، ما هیچ تضمینی
              را ارائه نمی دهیم یا قالب های وب سایت ضمانت نامه همانطور که ارائه
              می شود ، ارائه نمی دهیم.
            </p>
          </div>
          <div class="footersec1">
            <h2 class="text-2xl font-bold text-teal-400">شرکت</h2>
            <ul class="mt-5">
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
            <ul class="mt-5">
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
            <ul class="mt-5">
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
        </div>
      </div>
    </div>
    <div class="copyright text-center">
      <p>
        Copyright © and Designed By
        <span>RoyeshTeam</span>
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
}
.footer-btm-wrapper {
  padding-bottom: 80px;
  padding-top: 150px;
}
.footersec {
  width: 40%;
}
.footersec1 {
  width: 20%;
}
.footersec > p {
  color: #a2b2ff;
  width: 75%;
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
  border-top: 1px solid #7659e3;
  width: 100%;
}
.copyright p {
  font-size: 18px;
  margin: 0;
  padding: 30px 0;
  border: none;
  line-height: 14px;
  text-align: center;
  color: #a4acc4;
}
</style>
