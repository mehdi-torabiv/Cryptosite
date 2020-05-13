<template>
  <div class="container mx-auto text-center">
    <div class="header mt-12">
      <h2
        class="text-black text-xl font-bold mb-4"
        data-aos="fade-up"
        data-aos-delay="250"
        data-aos-once="true"
      >برای بروزرسانی اخبار در زمینه ارز دیجیتال عضو شوید!</h2>
      <p class="text-gray-600" data-aos="fade-down" data-aos-delay="250" data-aos-once="true">
        دستیار NRM مصنوعی مبتنی بر شبکه عصبی ، فوراً استفاده از داده های کاربر
        را تجزیه و تحلیل می کند.
      </p>
    </div>
    <form action="#" data-aos="fade-up" data-aos-delay="250" data-aos-once="true">
      <div class="inline-flex my-8">
        <button type="submit" class="text-center">ارسال</button>
        <input type="email" required placeholder="ایمیل خود را وارد کنید" />
      </div>
    </form>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
form input {
  width: 80%;
  height: 55px;
  border: 0 none;
  color: #a2b2ff;
  background: #ffffff;
  border-radius: 5px;
  padding: 0px 15px 0 70px;
  font-size: 22px;
  font-weight: 500;
  outline: none;
}

form button {
  border: 0 none;
  border-radius: 0 5px 5px 0;
  background: linear-gradient(-45deg, #9982ed 0%, #f879b6 100%);
  color: #ffffff;
  font-weight: bold;
  width: 185px;
  height: 55px;
  font-size: 18px;
  box-shadow: 0 0 15px 0 rgba(0, 0, 0, 0.3);
}
</style>
