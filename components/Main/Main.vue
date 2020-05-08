<template>
  <div>
    <div class="container mx-auto">
      <EarningWrapper></EarningWrapper>
      <AboutCrypto></AboutCrypto>
    </div>
    <pricingCharts></pricingCharts>
    <MultipleIncome></MultipleIncome>
    <ServiceSection></ServiceSection>
  </div>
</template>

<script>
import EarningWrapper from "./EarningWrapper/EarningWrapper";
import AboutCrypto from "./AboutCrypto/AboutCrypto";
import pricingCharts from "./pricingCharts/pricingCharts";
import MultipleIncome from "./MultipleIncome/MultipleIncome";
import ServiceSection from "./ServiceSection/ServiceSection";
export default {
  components: {
    EarningWrapper,
    AboutCrypto,
    pricingCharts,
    MultipleIncome,
    ServiceSection
  }
};
</script>

<style></style>
