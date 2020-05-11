<template>
  <div class="blog">
    <div class="blognav mb-12">
      <NavigationBar></NavigationBar>
    </div>
    <div class="container mx-auto">
      <div class="sub-title-blog py-12">
        <h2 class="header-title-blog text-center">بلاگ و رسانه سایت نیکوبیت</h2>
        <p class="subtitle-blog text-center text-gray-600">
          پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت
        </p>
      </div>
      <div class="blogs inline-flex">
        <SingleBlog :imagedata="Blogimg1"></SingleBlog>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import NavigationBar from "../components/NavigationBar/NavigationBar";
import SingleBlog from "../components/BlogSection/SingleBlog/SingleBlog";
import Footer from "../components/Footer/Footer";

import Blog3 from "../assets/images/blog/blog-03.jpg";
export default {
  data() {
    return {
      Blogimg1: Blog3
    };
  },
  components: {
    NavigationBar: NavigationBar,
    SingleBlog,
    Footer
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
