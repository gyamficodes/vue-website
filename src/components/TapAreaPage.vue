<template>
  <section class="Tap-Page" :style="`background: url(${pic})`">
    <div class="Tap-content">
      <div class="container">
        <div class="Tap-text">
          <div class="text-content">
            <h3>service</h3>
            <h1>Provide Exclusive Services</h1>
            <div class="line"></div>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
              eiusm tempor incididunt ut labore <br />
              et dolore magna aliqua. Ut enim advis minim veniam, quis nostrud
              exercitat
            </p>
           
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import image from "../assets/slider-4.jpg";

export default {
  name: "TapAreaPage",
  data() {
    return {
      pic: image,
    };
  },
  methods: {},
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/TapPage";
</style>
