<template>
  <div class="popular-tag mx-auto p-4 my-8 overflow-hidden">
    <h2 class="title my-3 text-xl pr-4 text-black">محبوبترین ها</h2>
    <ul class="inline-flex float-right mr-4 ">
      <li>
        <a href="#">بلاکچین</a>
      </li>
      <li>
        <a href="#">نیکوبیت</a>
      </li>
      <li>
        <a href="#">اتریوم</a>
      </li>
      <li>
        <a href="#">رمزنگاری</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.popular-tag {
  box-shadow: 0 1px 2px 1px rgba(0, 0, 0, 0.116);
}
.popular-tag ul {
  white-space: nowrap;
}
.popular-tag ul li {
  list-style: none;
  margin: 25px auto;
  margin-right: 10px;
}
.popular-tag ul li a {
  padding: 8px 12px;
  transition: all 0.1s ease-in-out;
  color: #7a839e;
  font-weight: 500;
  border-radius: 2px;
  border: 1px solid #ebd8f4;
}
.popular-tag ul li a:hover {
  background: linear-gradient(to left, #f879b6 0%, #9982ed 100%);
  color: white;
  transition: all 0.3s ease-in-out;
}
</style>
