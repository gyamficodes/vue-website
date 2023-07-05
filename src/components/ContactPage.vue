<template>
  <section class="ContactPage" :style="`background-image: url(${pic})`">
    <div class="contact-page-menu">
      <div class="contact">
        <ditv class="contactpage-top">
        <h4>GET QUOTE</h4>
        <h1>Make An <br> Free Consultant</h1>
        <div class="line"></div>
        </ditv>
      <ditv class="contactpage-down"></ditv>
      </div>
    </div>
  </section>
</template>

<script>
import image from "../assets/bg-cnt.jpg";
export default {
  name: "ContactPage",
  components: {},
  props: [],
  data() {
    return {
      pic: image,
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/ContactPage";
</style>
