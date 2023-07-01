<template>
  <section class="choosePage" :style="`background-image:url(${background})`">
    <div class="container">
      <div class="choose-content">
        <div class="choose">
          <h3>service</h3>
          <h1>Provide Exclusive Services</h1>
          <div class="line"></div>
          <div class="card-page">
            <div class="card" :style="`background: url(${item.pic})`" v-for="item in cards" :key="item.id">
              <span class="material-icons">{{ item.icon }}</span>
              <h2>{{ item.title }}</h2>
              <p>
               {{ item.text }}
              </p>
              <div class="btn">{{ item.btn }}</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import image from "../assets/slider-4.jpg";
import wh1 from "../assets/wh1.jpg";
import wh2 from "../assets/wh2.jpg";
import wh3 from "../assets/wh3.jpg";

export default {
  name: "ChooseUsPage",
  data() {
    return {
      cards: [
        {
          id: 1,
          pic: wh1,
          btn: 'read more',
          icon: "desktop_windows",
          title: "Deep Expertise & Leadership",
          text: "  We have the technology and industry expertise to develop solutions that can connect people and businesses across a  variety of mobile devices.",
        },
        {
          id: 2,
          pic: wh2,
          btn: 'read more',
          icon: "youtube_searched_for",
          title: "Cross-Industry Expertise",
          text: "  We have the technology and industry expertise to develop solutions that can connect people and businesses across a  variety of mobile devices.",
        },
        {
          id: 3,
          pic: wh3,
          btn: 'read more',
          icon: "public",
          title: "Dedicated IT Solution",
          text: "  We have the technology and industry expertise to develop solutions that can connect people and businesses across a  variety of mobile devices.",
        },
      ],
      background: image,
    
    };
  },
  methods: {},
  mounted() {},
  computed: {},
  created() {},
};
</script>
<style lang="scss">
@import "../assets/Sass/ChooseUsPage";
</style>
