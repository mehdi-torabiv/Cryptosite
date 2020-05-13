<template lang="html">
  <div class="resnav" id="parentx">
    <vs-button @click="active = !active" color="white" type="filled" 
      >
      <align-justify-icon size="2x" class="custom-class" color="black"></align-justify-icon>
      </vs-button
    >
    <vs-sidebar
      parent="body"
      default-index="1"
      color="primary"
      class="sidebarx"
      spacer
      v-model="active"
      position-right="true"
    >
    <vs-sidebar-item index="1" href="#header" v-scroll-to="'#header'" >
        <img src="../../../assets/images/gradient-logo.png"  alt="">
      </vs-sidebar-item>
      <vs-sidebar-item index="2" href="#header" v-scroll-to="'#header'" >
        خانه
      </vs-sidebar-item>

      <vs-sidebar-item index="3"  href="#about" v-scroll-to="'#about'">
        درباره ما
      </vs-sidebar-item>

      <vs-sidebar-item index="3" href="#pricingcharts" v-scroll-to="'#pricingcharts'">
        فروش ارز
      </vs-sidebar-item>
      <vs-sidebar-item index="4" href="#services" v-scroll-to="'#services'">
        نقشه راه
      </vs-sidebar-item>
      <vs-sidebar-item index="5" href="#team" v-scroll-to="'#team'">
        تیم
      </vs-sidebar-item>
      <vs-sidebar-item index="6" href="#faqsec" v-scroll-to="'#faqsec'">
        پرسش و پاسخ
      </vs-sidebar-item>
      <vs-sidebar-item index="7" href="#Contactus" v-scroll-to="'#Contactus'">
        ارتباط با ما
      </vs-sidebar-item>
    </vs-sidebar>
  </div>
</template>

<script>
import { AlignJustifyIcon } from "vue-feather-icons";
export default {
  data: () => ({
    active: false
  }),
  components: {
    AlignJustifyIcon
  }
};
</script>
<style lang="stylus">
#parentx {
  position: fixed;
  right: 1rem;
  top: 1rem;
  z-index: 999;
}

.header-sidebar {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 100%;

  h4 {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;

    > button {
      margin-left: 10px;
    }
  }
}

.footer-sidebar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;

  > button {
    border: 0px solid rgba(0, 0, 0, 0) !important;
    border-left: 1px solid rgba(0, 0, 0, 0.07) !important;
    border-radius: 0px !important;
  }

  vs-component vs-button vs-button-null vs-button-filled {
    margin-right: 1rem;
  }
}
</style>
