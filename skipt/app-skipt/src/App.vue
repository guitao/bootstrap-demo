<template>
  <div id="app">
    <app-header></app-header>
    <app-section1></app-section1>
    <app-section2></app-section2>
    <app-section3></app-section3>
    <app-section4></app-section4>
    <app-section5></app-section5>
    <app-section6></app-section6>
    <app-section7></app-section7>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Section1 from "./components/Section1";
import Section2 from "./components/Section2";
import Section3 from "./components/Section3";
import Section4 from "./components/Section4";
import Section5 from "./components/Section5";
import Section6 from "./components/Section6";
import Section7 from "./components/Section7";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    "app-header": Header,
    "app-section1": Section1,
    "app-section2": Section2,
    "app-section3": Section3,
    "app-section4": Section4,
    "app-section5": Section5,
    "app-section6": Section6,
    "app-section7": Section7,
    'app-footer': Footer
  }
};
</script>

<style>
.special-heading-1 {
  font-size: 55px;
  font-weight: normal;
  color: #fff;
  font-family: "Roboto", arial, sans-serif;
  letter-spacing: -0.03em;
  margin-top: 0;
  margin-bottom: 20px;
}
@media (max-width: 992px) {
  .special-heading-1 {
    font-size: 40px !important;
    line-height: 1.2em !important;
  }
}
hr {
  width: 80px;
  height: 4px;
  background-color: #db6f6a;
}
</style>
