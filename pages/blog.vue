<template>
  <div class="blog">
    <div class="blognav">
      <NavigationBar></NavigationBar>
    </div>
    <div class="container mx-auto">
      <div class="sub-title-blog">
        <h2 class="title-blog">بلاگ و رسانه سایت نیکوبیت</h2>
        <p class="text-">پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت</p>
      </div>
    </div>
  </div>
</template>

<script>
import NavigationBar from "../components/NavigationBar/NavigationBar";
export default {
  components: {
    NavigationBar: NavigationBar
  }
};
</script>

<style scoped>
.blog {
  padding: 0;
  margin: 0;
}
.blognav {
  background: blueviolet;
}
.blog > .title-blog {
  font-size: 36px;
  margin-bottom: 15px;
  color: black !important;
  letter-spacing: 1px;
}
</style>