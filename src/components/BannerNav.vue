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
            <div class="nav-links">
              <ul>
                <li><a href="#">home</a><i class="fa-solid fa-chevron-down"></i>
                <div class="sub-menu1">
                <ul>
                  <li><a href="#">company</a></li>
                  <li><a href="#">service</a></li>
                  <li><a href="#">it solution</a></li>
                  <li><a href="#">element</a></li>
                  <li><a href="#">blog</a></li>
                  <li><a href="#">contact</a></li>
                </ul>
                </div>
                </li>
                <li><a href="#">company</a><i class="fa-solid fa-chevron-down"></i></li>
                <li><a href="#">service</a></li>
                <li><a href="#">it solution</a><i class="fa-solid fa-chevron-down"></i></li>
                <li><a href="#">element</a><i class="fa-solid fa-chevron-down"></i></li>
                <li><a href="#">blog</a><i class="fa-solid fa-chevron-down"></i></li>
                <li><a href="#">contact</a></li>
              </ul>
            </div>
            <div class="nav-btn">
            <span>get a quote</span>
            </div>
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
