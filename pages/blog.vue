<template>
  <div class="blog">
    <div class="blognav">
      <NavigationBar></NavigationBar>
    </div>
    <div class="container mx-auto">
      <div class="sub-title-blog py-12">
        <h2 class="header-title-blog text-center">بلاگ و رسانه سایت نیکوبیت</h2>
        <p class="subtitle-blog text-center text-gray-600">
          پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت
        </p>
      </div>
      <div class="blogmain">
        <div class="blogs sm:block-flex  md:inline-flex">
          <SingleBlog :imagesrc="imgblog1"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog2"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog3"> </SingleBlog>
        </div>
        <div class="blogs sm:block-flex  md:inline-flex">
          <SingleBlog :imagesrc="imgblog4"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog5"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog6"> </SingleBlog>
        </div>
        <div class="blogs sm:block-flex  md:inline-flex">
          <SingleBlog :imagesrc="imgblog7"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog8"> </SingleBlog>
          <SingleBlog :imagesrc="imgblog9"> </SingleBlog>
        </div>
      </div>
    </div>
    <email></email>
    <Footer></Footer>
  </div>
</template>

<script>
import NavigationBar from "../components/NavigationBar/NavigationBar";
import SingleBlog from "../components/BlogSection/SingleBlog/SingleBlog";
import Footer from "../components/Footer/Footer";
import Subscribe from "../components/BlogSection/Subscribe/Subscribe";
//image imports
import blog1 from "../assets/images/blog/blog-01.jpg";
import blog2 from "../assets/images/blog/blog-02.jpg";
import blog3 from "../assets/images/blog/blog-03.jpg";
import blog4 from "../assets/images/blog/blog-04.jpg";
import blog5 from "../assets/images/blog/blog-05.jpg";
import blog6 from "../assets/images/blog/blog-06.jpg";
import blog7 from "../assets/images/blog/blog-07.jpg";
import blog8 from "../assets/images/blog/blog-08.jpg";
import blog9 from "../assets/images/blog/blog-09.jpg";
export default {
  data() {
    return {
      imgblog1: blog1,
      imgblog2: blog2,
      imgblog3: blog3,
      imgblog4: blog4,
      imgblog5: blog5,
      imgblog6: blog6,
      imgblog7: blog7,
      imgblog8: blog8,
      imgblog9: blog9
    };
  },
  components: {
    NavigationBar: NavigationBar,
    SingleBlog,
    email: Subscribe,
    Footer
  },
  methods: {}
};
</script>

<style scoped>
.blog {
  padding: 0;
  margin: 0;
}
.blognav {
  background: rgb(55, 0, 254);
  background: linear-gradient(
    3deg,
    rgba(55, 0, 254, 1) 0%,
    rgba(130, 68, 217, 1) 91%,
    rgba(87, 34, 166, 1) 100%
  );
  transition: ease-in-out 1s;
}
.blog .header-title-blog {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: bold;
  color: black !important;
  letter-spacing: 1px;
}
</style>
