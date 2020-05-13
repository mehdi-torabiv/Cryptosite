<template>
  <div id="index" class>
    <Header></Header>
    <Main></Main>
  </div>
</template>

<script>
import Header from "../components/Header/Header";
import Main from "../components/Main/Main";
export default {
  components: {
    Header,
    Main
  }
};
</script>

<style>
body {
  overflow-x: hidden;
}
</style>
