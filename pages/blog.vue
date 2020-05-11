<template>
  <div class="blog">
    <div class="blognav mb-12">
      <NavigationBar></NavigationBar>
    </div>
    <div class="container mx-auto">
      <div class="sub-title-blog py-12">
        <h2 class="header-title-blog text-center">بلاگ و رسانه سایت نیکوبیت</h2>
        <p
          class="subtitle-blog text-center text-gray-600"
        >پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت</p>
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
.blog .header-title-blog {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: bold;
  color: black !important;
  letter-spacing: 1px;
}
</style>