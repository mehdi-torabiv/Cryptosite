<template>
  <div class="mx-auto">
    <SearchBar></SearchBar>
    <Category></Category>
    <AboutCompany></AboutCompany>
  </div>
</template>

<script>
import SearchBar from "../../SearchBar/SearchBar";
import Category from "../Category/Category";
import AboutCompany from "../AboutCompany/AboutCompany";
export default {
  components: {
    SearchBar,
    Category,
    AboutCompany
  }
};
</script>

<style></style>
