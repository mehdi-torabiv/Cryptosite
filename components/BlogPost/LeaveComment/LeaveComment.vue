<template>
  <div class="container mx-auto">
    <div class="items-title">
      <h2>ثبت نظر</h2>
      <Email></Email>
    </div>
  </div>
</template>

<script>
import PostComment from "../../PostComment/PostComment";
export default {
  components: {
    Email: PostComment
  }
};
</script>

<style scoped>
h2 {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: normal;
  color: black !important;
  letter-spacing: 1px;
}
</style>
