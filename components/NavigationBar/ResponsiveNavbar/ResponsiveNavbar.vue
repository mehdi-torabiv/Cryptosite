<template>
  <div class="resnav">
    <vs-navbar
      collapse
      v-model="activeItem"
      class="nabarx"
      color="#020c59"
      text-color="white"
      active-text-color="white"
    >
      <div slot="title">
        <vs-navbar-title>
          <img src="../../../assets/images/logo.png" alt="" />
        </vs-navbar-title>
      </div>

      <vs-navbar-item index="0">
        <a href="#">خانه</a>
      </vs-navbar-item>
      <vs-navbar-item index="1">
        <a href="#about" v-scroll-to="'#about'">درباره</a>
      </vs-navbar-item>
      <vs-navbar-item index="2">
        <a href="#pricingcharts" v-scroll-to="'#pricingcharts'">فروش ارز</a>
      </vs-navbar-item>
      <vs-navbar-item index="3">
        <a href="#services" v-scroll-to="'#services'">نقشه راه</a>
      </vs-navbar-item>
      <vs-navbar-item index="4">
        <a href="#team" v-scroll-to="'#team'">تیم</a>
      </vs-navbar-item>
      <vs-navbar-item index="5">
        <a href="#Contactus" v-scroll-to="'#Contactus'">ارتباط با ما</a>
      </vs-navbar-item>
    </vs-navbar>
  </div>
</template>
<script>
export default {
  data: () => ({
    activeItem: 0
  })
};
</script>
<style>
.resnav {
  position: fixed;
  width: 100%;
}
</style>
