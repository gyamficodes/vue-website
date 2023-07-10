<template>
  <section class="RequesstPage" :style="`background-image: url(${image})1`">
    <div class="container">
      <div class="Request-page-content">
        <div class="Request-content">
          <h4>+880 013 143 206</h4>
          <h1>
            To make requests for the <br />
            further information
          </h1>
          <div class="btn">
          <a href="#">join with now </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import pic from "../assets/call-bg.png";
export default {
  data() {
    return {
      image: pic,
    };
  },
  methods: {},
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/RequestPage";
</style>
