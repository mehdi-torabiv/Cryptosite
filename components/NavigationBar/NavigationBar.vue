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
          <a href="#" class="token">خرید ارز</a>
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
</style>
