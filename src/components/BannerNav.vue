<template>
  <section class="nav">
    <div class="container">
      <div class="nav-menu">
        <div class="nav-left">
          <div class="logo">
            <img :src="image" alt="" />
          </div>
        </div>
        <div class="nav-right">
          <div class="right-box">
            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import logo from "../assets/log.png";
export default {
  name: "BannerNav",
  components: {},
  data() {
    return {
      image: logo,
    };
  },
  methods: {},
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/BannerNav";
</style>
