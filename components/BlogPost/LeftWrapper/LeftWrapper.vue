<template>
  <div class="mx-auto">
    <Category></Category>
    <AboutCompany></AboutCompany>
    <PopularTags></PopularTags>
  </div>
</template>

<script>
import Category from "../Category/Category";
import AboutCompany from "../AboutCompany/AboutCompany";
import PopularTags from "../PopularTags/PopularTags";
export default {
  components: {
    Category,
    AboutCompany,
    PopularTags
  }
};
</script>

<style></style>
