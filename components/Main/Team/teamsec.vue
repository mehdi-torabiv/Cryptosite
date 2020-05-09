<template>
  <div class="team-membar">
    <div class="container">
      <div class="sub-title">
        <h2>
          تیم ما
        </h2>
        <p>
          با توجه به استفاده از قدرت محاسباتی بزرگ ، دستیار بلافاصله راه حل های
          ارائه داده های کاربر را برای استفاده بیشتر آنها مورد تجزیه و تحلیل
          قرار می دهد.
        </p>
      </div>
    </div>
    <div class="container">
      <div class="owlCarousel owl-carousel owl-theme">
        <div class="owl-wrapper-outer">
          <div class="owl-wrapper">
            <div class="owl-item" style="width: 310px;">
              <img src="../../../assets/images/team/team-01.jpg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.owlCarousel .owl-carousel .owl-theme {
  opacity: 1;
  display: block;
}
.owl-wrapper {
  width: 2480px;
  left: 0px;
  display: block;
  transform: translate3d(0px, 0px, 0px);
  transition: all 0ms ease 0s;
}
#team_membar {
  background: #020c56;
  padding: 150px 0;
}
#team_membar .single-row {
  margin-bottom: 40px;
}
#team_membar .single-row:last-child {
  margin-bottom: 0;
}
#team_membar .single-row .team-single-item {
  overflow: hidden;
}
#team_membar .single-row .team-single-item figure {
  position: relative;
  margin: 0;
}
#team_membar .single-row .team-single-item figure .member-img {
  position: relative;
}
#team_membar .single-row .team-single-item figure .member-img:before {
  background: #0b1e68;
  opacity: 0.45;
  content: "";
  left: 0;
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
  transition: all 0.3s ease 0s;
}
#team_membar .single-row .team-single-item figure .member-img img {
  width: 100%;
}
#team_membar .single-row .team-single-item figure figcaption {
  content: "";
  left: 0;
  bottom: 0;
  position: absolute;
  transition: all 0.3s ease 0s;
  width: 100%;
}
#team_membar .single-row .team-single-item figure figcaption .member-name {
  transition: all 0.3s ease-in-out;
  text-align: left;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 15px 0;
  margin-left: 40px;
}
#team_membar .single-row .team-single-item figure figcaption .member-name h4 {
  transition: all 0.3s ease-in-out;
  color: #ffffff;
  font-size: 20px;
  font-weight: 600;
  margin: 0;
  text-transform: uppercase;
}
#team_membar .single-row .team-single-item figure figcaption .member-name span {
  transition: all 0.3s ease-in-out;
  font-size: 14px;
  transition: all 0.3s ease 0s;
}
#team_membar .single-row .team-single-item figure figcaption .social-links {
  background: linear-gradient(to right, #f78ca0, #fe9a8b);
  margin: 0px auto;
  text-align: left;
  padding-left: 40px;
  height: 55px;
  visibility: hidden;
  opacity: 0;
  transition: all 0.3s ease-in-out;
  margin-bottom: -55px;
}
#team_membar .single-row .team-single-item figure figcaption .social-links li {
  display: inline-flex;
  margin-right: 15px;
  line-height: 55px;
}
#team_membar
  .single-row
  .team-single-item
  figure
  figcaption
  .social-links
  li
  a {
  color: #0b1e68;
  font-size: 18px;
  transition: all 0.3s ease 0s;
}
#team_membar
  .single-row
  .team-single-item
  figure
  figcaption
  .social-links
  li
  a:hover {
  color: #26e48a;
}
#team_membar .single-row .team-single-item figure:hover .member-img:before {
  opacity: 0.2;
}
#team_membar .single-row .team-single-item figure:hover figcaption {
  transition: all 0.3s ease-in-out;
}
#team_membar
  .single-row
  .team-single-item
  figure:hover
  figcaption
  .social-links {
  visibility: visible;
  opacity: 1;
  margin-bottom: 0px;
}
</style>
