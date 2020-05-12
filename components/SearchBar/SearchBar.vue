<template>
  <form action="#" class="w-full inline-flex mb-2">
    <button class="w-1/12 ml-2"></button>
    <input class="w-11/12" type="text" name="" placeholder="جستجو..." id="" />
  </form>
</template>

<script>
export default {
  components: {}
};
</script>

<style scoped>
input {
  height: 58px;
  padding-right: 20px;
  font-size: 16px;
  color: #8d95a6;
  border-radius: 3px;
  box-shadow: none;
  outline: none;
  overflow: visible;
}
input:focus,
button:focus {
  box-shadow: 0 3px 4px 1px rgba(0, 0, 0, 0.062);
  transition: 0.3s ease-in-out;
  outline: none;
}
button {
  height: 58px !important;
  border: none;
  background: url("../../assets/images/icons/search-icon.png") no-repeat center,
    linear-gradient(to left, #f879b6 0%, #9982ed 100%);
  width: 58px;
  border-radius: 3px;
  height: 30px;
  float: right;
  cursor: pointer;
}
</style>
