<template>
  <section class="choosePage" :style="`background-image:url(${background})`">
    <div class="container">
      <div class="choose-content">
        <div class="choose">
          <h3>service</h3>
          <h1>Provide Exclusive Services</h1>
          <div class="line"></div>
          <div class="card-page">
            <div class="card" :style="`background: url(${pic1})`">
              <span class="material-icons">desktop_windows</span>
              <h2>Deep Expertise & Leadership</h2>
              <p>
                We have the technology and industry expertise to develop
                solutions that can connect people and businesses across a
                variety of mobile devices.
              </p>
              <div class="btn">read more</div>
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
          icon: "desktop_windows",
          title: "Cross-Industry Expertise",
          text: "  We have the technology and industry expertise to develop solutions that can connect people and businesses across a  variety of mobile devices.",
        },
        {
          id: 3,
          pic: wh3,
          btn: 'read more',
          icon: "desktop_windows",
          title: "Dedicated IT Solution",
          text: "  We have the technology and industry expertise to develop solutions that can connect people and businesses across a  variety of mobile devices.",
        },
      ],
      background: image,
      pic1: wh1,
      pic2: wh2,
      pic3: wh3,
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
