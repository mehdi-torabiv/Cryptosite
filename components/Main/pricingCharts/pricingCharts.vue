<template>
  <div class="pricingCharts" id="pricingcharts">
    <div class="container mx-auto">
      <h2
        class="text-center"
        data-aos="fade-up"
        data-aos-duration="950"
        data-aos-ease="ease-in"
      >نمودار قیمت</h2>
      <div class="chart">
        <img class="mx-auto" src="../../../assets/images/priceing-chats-02.png" alt />
        <button data-aos="fade-in" data-aos-duration="750" data-aos-ease="ease-in">نمایش جدول ها</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.pricingCharts {
  position: relative;
  padding: 50px 0;
}
.pricingCharts:before {
  position: absolute;
  background: url("../../../assets/images/priceing-chats-bg-shpe.png") no-repeat
    100% 100%;
  content: "";
  height: 100%;
  width: 100%;
  left: 0;
  bottom: 50%;
  transform: translateY(20%);
  z-index: -999;
}
.pricingCharts .chart {
  text-align: center;
}
.pricingCharts h2 {
  font-size: 36px;
  font-weight: 500;
  line-height: 46px;
  margin-bottom: 40px;
  color: #19233b;
}
button {
  font-size: 22px;
  padding: 9px 25px;
  border-radius: 50px;
  text-transform: capitalize;
  font-weight: 600;
  background: #007bff;
  color: #ffffff;
}
button:hover {
  background: #00e9fe;
  color: #ffffff;
  transition: ease-in-out 0.3s;
  outline: none;
}
</style>
