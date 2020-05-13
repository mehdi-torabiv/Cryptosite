<template>
  <div class="comment mt-5">
    <form action="#">
      <div class="block-flex w-full mb-2">
        <div class="w-full pl-2 py-2">
          <input type="text" placeholder="نام و نام خانوادگی" name id />
        </div>
        <div class="w-full pl-2 py-2">
          <input type="text" placeholder="ایمیل خود را وارد کنید" name id required />
        </div>
      </div>
      <div class="pl-2">
        <textarea name placeholder="پیغام خود را بنویسید" id cols="30" rows="10"></textarea>
      </div>
      <div class="submit-btn my-4 w-full text-center pl-2">
        <button>ارسال پیغام</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.comment input,
.comment textarea {
  width: 100%;
  height: 58px;
  padding-right: 10px;
  font-size: 16px;
  color: #8d95a6;
  border-radius: 3px;
  outline: none;
  border: 1px solid rgba(0, 0, 0, 0.13);
}
.comment textarea:focus,
.comment input:focus {
  box-shadow: 0 1px 1px 1px rgba(0, 0, 0, 0.055);
  transition: 0.3s all ease-in-out;
}
.comment textarea {
  resize: none;
  height: 140px;
  padding-top: 0.8rem;
}
.comment .submit-btn {
  background: linear-gradient(to left, #f879b6 0%, #9982ed 100%);
  padding: 9px 25px;
  border-radius: 4px;
  font-size: 14px;
  text-transform: capitalize;
  font-weight: 600;
  border: none;
  cursor: pointer;
  color: #fff;
}
.comment .submit-btn:hover {
  box-shadow: 0 2px 3px 2px rgba(0, 0, 0, 0.137);
  transition: all 0.3s ease-in-out;
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
    height: 35px;
  }
}
</style>
