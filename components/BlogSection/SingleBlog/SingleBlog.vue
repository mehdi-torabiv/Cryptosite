<template>
  <div id="singleBlog" class="md:w-1/3 justify-center">
    <div class="blog-img" slot="blogimg">
      <a href="#">
        <img :src="imagedata" alt class="video-ifram" />
      </a>
      <a href>
        <play-icon class="custom-class"></play-icon>
      </a>
    </div>
    <div class="blog-title">
      <span class="text-sm">12 مهرماه 1399</span>
      <h3 class="mt-3 font-normal">
        <a href>IBM اثبات برای کار بلاکچین</a>
      </h3>
      <div class="blog-meta mt-3 ">
        <span class="ago text-sm text-gray-600">1 ساعت پیش</span>
        <ul class="share_options float-left ">
          <li>
            <a href>
              <img src="../../../assets/images/blog/bicon-01.png" alt />
            </a>
          </li>
          <li>
            <a href>
              <img src="../../../assets/images/blog/bicon-02.png" alt />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import { PlayIcon } from "vue-bytesize-icons";

export default {
  props: {
    imagedata: {
      type: String,
      default: null
    }
  },
  components: { PlayIcon }
};
</script>

<style>
#singleBlog {
  padding: 15px;
  background: blanchedalmond;
  margin-bottom: 30px;
  max-width: 33.3333%;
  margin-left: 1rem;
}
#singleBlog .blog-img img {
  border-radius: 3px;
}
#singleBlog > a > img {
  max-width: 100%;
  height: auto;
}
#singleBlog > .blog-img:nth-child(2) #i-play {
  position: relative;
  left: 0 !important;
}
#singleBlog .share_options li {
  display: inline-block;
}
#singleBlog .share_options > li > a > img {
  vertical-align: middle;
}
</style>
