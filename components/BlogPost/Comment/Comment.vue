<template>
  <div class="container mx-auto">
    <div class="comment w-full flex inline-flex pb-8">
      <div class="author-img">
        <img :src="imgOne" alt="" />
      </div>

      <div class="comment-text mr-6 text-lg w-full">
        <div class="author-info flex inline-flex mb-4">
          <a href="" class="author-name text-gray-500 ml-4">
            سارا شمس
          </a>
          <span class="date-comment text-gray-500">
            12مهر 1397
          </span>
        </div>
        <p class="text-right text-gray-600 ">
          بهترین بلاگ برای اخبار به روز درباره ارز دیجیتال.
        </p>
      </div>
      <div class="reply justify-end">
        <a href="" class="text-lg">پاسخ</a>
      </div>
    </div>
    <slot name="reply"></slot>
  </div>
</template>

<script>
export default {
  props: {
    imgOne: {
      type: String,
      default: null
    }
  },
  components: {}
};
</script>

<style scoped>
img {
  max-height: 80px;
  max-width: 80px;
  border-radius: 5px;
}
.reply {
  background-image: linear-gradient(to left, #9982ed 0%, #f879b6 100%);
  color: transparent;
  -webkit-background-clip: text;
  font-size: 14px;
  margin-right: 15px;
}
.reply > a:hover,
.reply > a:focus {
  transition: all 0.3s ease-in-out;
  text-decoration: none;
  outline: none;
}
</style>
