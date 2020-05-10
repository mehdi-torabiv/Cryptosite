<template>
  <nav
    class="navbar"
    :class="{
      stickyClass: scrollPosition < 100,
      fixedClass: scrollPosition > 100
    }"
  >
    <div class="container mx-auto">
      <ul>
        <li>
          <a class="token">خرید ارز</a>
        </li>
        <li>
          <a href="#header" v-scroll-to="'#header'">خانه</a>
        </li>
        <li>
          <a href="#about" v-scroll-to="'#about'">درباره</a>
        </li>
        <li>
          <a href="#pricingcharts" v-scroll-to="'#pricingcharts'">فروش ارز</a>
        </li>
        <li>
          <a href="#services" v-scroll-to="'#services'">نقشه راه</a>
        </li>
        <li>
          <a href="#team" v-scroll-to="'#team'">تیم</a>
        </li>
        <li>
          <a href="#faqsec" v-scroll-to="'#faqsec'">پرسش و پاسخ</a>
        </li>
        <li>
          <a href="#Contactus" v-scroll-to="'#Contactus'">ارتباط با ما</a>
        </li>
        <div class="spacer"></div>
        <div class="navBrand inline-block">
          <img src="../../assets/images/logo.png" alt />
        </div>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  data: function() {
    return {
      scrollPosition: null
    };
  },

  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY;
    }
  },

  mounted() {
    window.addEventListener("scroll", this.updateScroll);
  },
  destroy() {
    window.removeEventListener("scroll", this.updateScroll);
  }
  //destroy() {
  //window.removeEventListener("scroll", this.updateScroll);
  //}
};
</script>

<style scoped>
nav {
  position: fixed;
  width: 100%;
  padding: 25px 0 0;
  z-index: 1;
}
.stickyClass {
  position: sticky;
}
.fixedClass {
  position: fixed;
  background: rgb(55, 0, 254);
  background: linear-gradient(
    3deg,
    rgba(55, 0, 254, 1) 0%,
    rgba(130, 68, 217, 1) 91%,
    rgba(87, 34, 166, 1) 100%
  );
  transition: ease-in-out 1s;
  padding-top: 10px;
  margin-top: auto;
}
.navBrand {
  padding: 25px 0;
}
.spacer {
  flex: 1;
}
ul {
  display: flex;
  flex-direction: row;
}
ul li {
  padding: 30px 0;
  font-size: 15px;
  color: white;
}
ul li {
  margin-right: 30px;
}
ul li:last-child {
  margin-right: 0px;
}
ul li a {
  padding: 30px 0px;
  color: #ffffff;
  font-size: 15px;
  text-transform: none;
}
ul li a.active,
ul li a:hover {
  color: #43d796;
}
.token {
  background: #00e9fe;
  padding: 9px 25px;
  border-radius: 50px;
  font-size: 14px;
  text-transform: capitalize;
  font-weight: 600;
  color: #ffffff;
}
.token:hover {
  background: #007bff;
  color: #ffffff;
}
.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}
</style>
