<template>
  <div id="index">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../components/Header/Header";
import Main from "../components/Main/Main";
import Footer from "../components/Footer/Footer";
export default {
  components: {
    Header,
    Main,
    Footer
  }
};
</script>

<style>
body {
  overflow-x: hidden;
}
</style>
