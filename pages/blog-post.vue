<template>
  <div class="bg-blog sm:overflow-x-scroll md:overflow-x-hidden">
    <div class="blognav">
      <NavigationBar></NavigationBar>
      <ResponsiveNavbar></ResponsiveNavbar>
    </div>
    <div class="blog-post">
      <div class="main-blog container mx-auto my-12">
        <div
          class="header-blog-post mb-4"
          data-aos="fade-right"
          data-aos-delay="500"
          data-aos-once="true"
        >
          <h2>وبلاگ ما</h2>
          <p class="text-gray-600">پیشرفت چشمگیر در بیزینس به واسطه سایت نیکوبیت</p>
        </div>
        <div
          class="postarea-blog-post"
          data-aos="fade-right"
          data-aos-delay="500"
          data-aos-once="true"
        >
          <img class="mx-auto w-full mb-12" src="../assets/images/blog/post.jpg" alt />
        </div>
        <div class="blog-post-wrapper inline-flex">
          <div
            class="blog-details ml-5 sm:w-full px-8 md:w-2/3"
            data-aos="fade-up"
            data-aos-delay="500"
            data-aos-once="true"
          >
            <div class="header-blog-post-wrapper">
              <h2>ارتباطات اکوسیستم بیت کوین راه تضعیف میکند.</h2>
              <div class="author-info my-8">
                <span class="ml-12 text-gray-600">پست شده در تاریخ 18 آذر 1399</span>
                <span class="text-gray-600">توسط - مهدی ترابی</span>
              </div>
            </div>
            <div class="detail-blog-post-wrapper text-justify sm:p-8">
              <p class="text-gray-600 text-md leading-snug font-bold mb-6">
                اولین تغییر مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا
                خلاقیت مدل سوختگی آندروید بوم بتا خلاق میزان سوختگی آندروید
                کاربر گرافیکی. اولین مزیت متحرک تبدیل استقرار ramen تبدیل اولین
                مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا مدل سوزش آندروید
                خلاق بوم بتا آندروید خلاق میزان سوختگی گرافیکی. اولین بار
                استقرار مزیت انتقال حرکت
              </p>
              <p class="text-gray-600 text-md leading-snug font-bold mb-6">
                اولین تغییر مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا
                خلاقیت مدل سوختگی آندروید بوم بتا خلاق میزان سوختگی آندروید
                کاربر گرافیکی. اولین مزیت متحرک تبدیل استقرار ramen تبدیل اولین
                مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا مدل سوزش آندروید
                خلاق بوم بتا آندروید خلاق میزان سوختگی گرافیکی. اولین بار
                استقرار مزیت انتقال حرکت
              </p>
              <p class="text-gray-600 text-md leading-snug font-bold mb-6">
                اولین تغییر مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا
                خلاقیت مدل سوختگی آندروید بوم بتا خلاق میزان سوختگی آندروید
                کاربر گرافیکی. اولین مزیت متحرک تبدیل استقرار ramen تبدیل اولین
                مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا مدل سوزش آندروید
                خلاق بوم بتا آندروید خلاق میزان سوختگی گرافیکی. اولین بار
                استقرار مزیت انتقال حرکت
              </p>
              <p class="text-gray-600 text-md leading-snug font-bold mb-6">
                اولین تغییر مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا
                خلاقیت مدل سوختگی آندروید بوم بتا خلاق میزان سوختگی آندروید
                کاربر گرافیکی. اولین مزیت متحرک تبدیل استقرار ramen تبدیل اولین
                مزیت متحرک ramen استقرار مدل کسب و کار بوم بتا مدل سوزش آندروید
                خلاق بوم بتا آندروید خلاق میزان سوختگی گرافیکی. اولین بار
                استقرار مزیت انتقال حرکت
              </p>
            </div>
            <div class="comment">
              <h2>
                <span>2</span>نظر
              </h2>
              <Comment :imgOne="imgOne"></Comment>
              <Comment :imgOne="imgTwo"></Comment>
            </div>
            <LeaveComment></LeaveComment>
          </div>
          <div
            class="md:w-1/3 text-right text-gray-600"
            data-aos="fade-down"
            data-aos-delay="500"
            data-aos-once="true"
          >
            <LeftWrapper></LeftWrapper>
          </div>
        </div>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
import NavigationBar from "../components/NavigationBar/NavigationBar";
import ResponsiveNavbar from "../components/NavigationBar/ResponsiveNavbar/ResponsiveNavbar";
import Comment from "../components/BlogPost/Comment/Comment";
import LeaveComment from "../components/BlogPost/LeaveComment/LeaveComment";
import Footer from "../components/Footer/Footer";
//leftwrapper imported;
import LeftWrapper from "../components/BlogPost/LeftWrapper/LeftWrapper";
//import images
import user1 from "../assets/images/blog/user-01.png";
import user2 from "../assets/images/blog/user-02.png";
export default {
  data() {
    return {
      imgOne: user1,
      imgTwo: user2
    };
  },
  components: {
    LeftWrapper,
    NavigationBar,
    ResponsiveNavbar,
    Comment,
    LeaveComment,
    Footer
  }
};
</script>

<style scoped>
.bg-blog {
  background: #e6e6e6;
}
.main-blog {
  margin: 120px auto;
  background: white;
  padding: 20px;
  border-radius: 5px;
}
.blog-post {
  margin: 0;
  padding: 0;
}
.postarea-blog-post {
  margin: 0 -20px;
}
.blognav {
  background: rgb(55, 0, 254);
  background: linear-gradient(
    3deg,
    rgba(55, 0, 254, 1) 0%,
    rgba(130, 68, 217, 1) 91%,
    rgba(87, 34, 166, 1) 100%
  );
  transition: ease-in-out 1s;
}
h2 {
  font-size: 36px !important;
  margin-bottom: 15px;
  font-weight: normal;
  color: black !important;
  letter-spacing: 1px;
}
.comment > h2 {
  /**/
}
</style>
