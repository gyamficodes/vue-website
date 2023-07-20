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
            <div class="card" v-for="blog in blogCards" :key="blog.id">
              <div
                class="card-img"
                :style="`background: url(${blog.blog})`"
              ></div>
              <div class="card-body">
                <div class="date">
                  <a href="#">{{ blog.dateText }}</a>
                  <span></span>
                  <h5>{{ blog.date }}</h5>
                </div>
                <a class="title" href="#">{{ blog.title }}</a>
                <p>{{ blog.myText }}</p>
                <div class="box-text">
                  <h4>{{ blog.btn }}</h4>
                  <span class="material-icons">{{ blog.icon }}</span>
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
import blog2 from "../assets/blog2.jpg";
import blog3 from "../assets/blog3.jpg";

export default {
  name: "BlogPage",
  components: {},
  props: [],
  data() {
    return {
      blogCards: [
        {
          id: 1,
          title: "The five devices you need to work anytime",
          blog: blog1,
          myText:
            "Lorem ipsum dolor sit amet consectet adipisie cing elit sed eiusmod tempor incididunt on labore et dolore.",
          btn: "read more",
          icon: "arrow_right_alt",
          dateText: "Techno",
          date: "January 3, 2023",
        },
        {
          id: 1,
          title: "How to learn PHP 10 tips to get you started",
          blog: blog2,
          myText:
            "Lorem ipsum dolor sit amet consectet adipisie cing elit sed eiusmod tempor incididunt on labore et dolore.",
          btn: "read more",
          icon: "arrow_right_alt",
          dateText: "Techno",
          date: "December 3, 2023",
        },
        {
          id: 1,
          title: "The five devices you need to work anytime",
          blog: blog3,
          myText:
            "Lorem ipsum dolor sit amet consectet adipisie cing elit sed eiusmod tempor incididunt on labore et dolore.",
          btn: "read more",
          icon: "arrow_right_alt",
          dateText: "Techno",
          date: "Augost 5, 2023",
        },
      ],
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
