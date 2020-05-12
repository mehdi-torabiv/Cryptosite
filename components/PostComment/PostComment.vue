<template>
  <div class="comment mt-5">
    <form action="#">
      <div class="inline-flex w-full mb-4">
        <div class="w-1/2 pl-2">
          <input type="text" placeholder="نام و نام خانوادگی" name="" id="" />
        </div>
        <div class="w-1/2 pr-2">
          <input
            type="text"
            placeholder="ایمیل خود را وارد کنید"
            name=""
            id=""
            required
          />
        </div>
      </div>
      <div>
        <textarea
          name=""
          placeholder="پیغام خود را بنویسید"
          id=""
          cols="30"
          rows="10"
        ></textarea>
      </div>
      <div class="submit-btn my-8 w-1/5">
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
}
.comment textarea:focus,
.comment input:focus {
  box-shadow: 0 1px 2px 2px rgba(0, 0, 0, 0.144);
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
</style>
