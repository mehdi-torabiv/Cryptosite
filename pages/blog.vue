
<template>
  <div class="bg-blog sm:overflow-x-scroll md:overflow-x-hidden">
    <div class="blog-post container mx-auto my-12">
      <div class="main-blog">
        <div
            class="sub-title-blog py-12"
            data-aos="fade-up"
            data-aos-delay="900"
            data-aos-once="true"
          >
            <h2 class="header-title-blog text-center">بلاگ و رسانه سایت نیکوبیت</h2>
            <p
              class="subtitle-blog text-center text-gray-600"
            >پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت</p>
          </div>
          <div class="blogmain">
            <div class="mx-8 mx-auto">
              <SearchBar></SearchBar>
            </div>
            <div class="blogs sm:block-flex md:inline-flex">
              <SingleBlog :imagesrc="imgblog1"></SingleBlog>
              <SingleBlog :imagesrc="imgblog2"></SingleBlog>
              <SingleBlog :imagesrc="imgblog3"></SingleBlog>
            </div>
            <div class="blogs sm:block-flex md:inline-flex">
              <SingleBlog :imagesrc="imgblog4"></SingleBlog>
              <SingleBlog :imagesrc="imgblog5"></SingleBlog>
              <SingleBlog :imagesrc="imgblog6"></SingleBlog>
            </div>
            <div class="blogs sm:block-flex md:inline-flex">
              <SingleBlog :imagesrc="imgblog7"></SingleBlog>
              <SingleBlog :imagesrc="imgblog8"></SingleBlog>
              <SingleBlog :imagesrc="imgblog9"></SingleBlog>
            </div>
          </div>
          <email></email>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SingleBlog from "../components/BlogSection/SingleBlog/SingleBlog";
import Subscribe from "../components/BlogSection/Subscribe/Subscribe";
import SearchBar from "../components/SearchBar/SearchBar";
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
    // NavigationBar: NavigationBar,
    // ResponsiveNavbar,
    SingleBlog,
    SearchBar,
    email: Subscribe
  },
  methods: {}
};
</script>

<style scoped>

.bg-blog {
  background: #e6e6e6;
}
.main-blog {
  background: white;
  padding: 20px;
  margin: 120px auto;
  border-radius: 5px;
}
.blog-post {
  padding: 0;margin: 0 auto;
}
.blog .header-title-blog {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: bold;
  color: black !important;
  letter-spacing: 1px;
}
h2 {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: normal;
  color: black !important;
  letter-spacing: 1px;
}
/* .comment > h2 {

} */

@media only screen and (max-width: 640px) {
  .blog-post .main-blog {
    margin: 50px auto;
  }
}
</style>
