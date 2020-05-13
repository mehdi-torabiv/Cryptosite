<template>
  <div>
    <div>
      <NavigationBar></NavigationBar>
      <ResponsiveNavbar></ResponsiveNavbar>
    </div>
    <nuxt />
    <div>
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import NavigationBar from "../components/NavigationBar/NavigationBar";
import ResponsiveNavbar from "../components/NavigationBar/ResponsiveNavbar/ResponsiveNavbar";
import Footer from "../components/Footer/Footer";
export default {
  components: {
    NavigationBar,
    ResponsiveNavbar,
    Footer
  }
};
</script>
<style>
</style>
