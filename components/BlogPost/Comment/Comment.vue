<template>
  <div class="comments container mx-auto mb-6">
    <div class="comment py-8 px-4 sm:py-4 sm:w-1/3 md:w-full flex inline-flex">
      <div class="author-img">
        <img :src="imgOne" alt />
      </div>

      <div class="comment-text mr-6 text-lg w-full">
        <div class="author-info flex inline-flex mb-4">
          <a href class="author-name text-gray-500 ml-4">سارا شمس</a>
          <span class="date-comment text-gray-500">12مهر 1397</span>
        </div>
        <p class="text-right text-gray-600">بهترین بلاگ برای اخبار به روز درباره ارز دیجیتال.</p>
      </div>
      <div class="reply justify-end">
        <a href class="text-lg">پاسخ</a>
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
.comments {
  box-shadow: 0 2px 3px 1px rgba(0, 0, 0, 0.164);
  border-radius: 5px;
}
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
@media only screen and (max-width: 470px) {
  .comment {
    display: flex;
    flex-direction: column;
    padding: 25px;
  }
  .comment .submit-btn {
    text-align: center;
    padding: inherit;
    width: 100%;
  }
}
</style>
