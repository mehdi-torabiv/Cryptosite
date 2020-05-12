<template>
  <div class="Category mx-auto p-4 my-8">
    <h2 class="title my-3 text-xl pr-4 text-black">دسته بندی</h2>
    <ul class="block-flex my-4">
      <li>
        <a href="" class="flex justify-between px-4 my-1 text-md"
          >بیتکوین <span>25</span></a
        >
      </li>
      <li>
        <a href="" class="flex justify-between px-4 my-1 text-md"
          >رمزنگاری <span>50</span></a
        >
      </li>
      <li>
        <a href="" class="flex justify-between px-4 my-1 text-md"
          >نیکوبیت<span>70</span></a
        >
      </li>
      <li>
        <a href="" class="flex justify-between px-4 my-1 text-md"
          >بلاکچین <span>28</span></a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.Category {
  box-shadow: 0 1px 2px 1px rgba(0, 0, 0, 0.116);
}

.Category > ul > li > a:hover {
  color: blueviolet;
  transition: 0.3s ease-in-out;
}
</style>
