<template>
  <section class="Blog-Page">
    <div class="container">
      <div class="box">
        <div class="content" v-for="item in numbers" :key="item.id">
          <h1>{{ item.num }}</h1>
          <h3>{{ item.text }}</h3>
        </div>
      </div>
      <div class="page-content">
        <di class="page-area">
          <div class="topA">
            <h5>LATEST ARTICLE</h5>
            <h1>Our Latest Blog Posts</h1>
            <div class="line"></div>
          </div>
          <div class="downB">
            <div class="card">
              <div class="card-img" :style="`background: url(${blog})`"></div>
              <div class="card-body">
                <div class="date">
                <a href="#"></a>
                </div>
              </div>
            </div>
          </div>
        </di>
      </div>
    </div>
  </section>
</template>

<script>
import blog1 from "../assets/blog1.jpg";

export default {
  name: "BlogPage",
  components: {},
  props: [],
  data() {
    return {
      blog: blog1,
      numbers: [
        {
          id: 1,
          num: "15K",
          text: "Happy Clients",
        },
        {
          id: 1,
          num: "1280+",
          text: "Account Number",
        },
        {
          id: 1,
          num: "10K",
          text: "Finished Projects",
        },
        {
          id: 1,
          num: "992+",
          text: "Win Awards",
        },
      ],
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/BlogPage";
</style>
