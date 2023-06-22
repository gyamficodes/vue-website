<template>
  <section class="About-content">
    <div class="container">
      <div class="About-menu">
        <div class="page-text">
          <h2>about us</h2>
          <h1>
            Preparing For Your Success <br />
            Provide Best <span style="color: #0c5adb">IT Solutions.</span>
          </h1>
          <div class="line"></div>
          <h3>
            Voice and Data Systems are crucial to the success <br />
            or failure of most businesses. any companies provide laptops, cell
            phones.
          </h3>
          <div class="text-flex">
            <div class="bar"></div>
            <p>
              The standard chunk of Lorem Ipsum used since the 1500s is and
              reproduced below for those interested. Sections 1.10.32 and also
              1.10.33 from “de br Finibus Bonorum et Malorum" by Cicero are alse
              reproduced in their exact original form, accompanied
              <br />
              <br />
              The standard chunk of Lorem Ipsum used since the 1500s is and
              <br />
              reproduced below for those interested
            </p>
          </div>
          <div class="btn">
            <span>more details</span>
          </div>
        </div>
        <div class="page-image">
          <div class="anima-image">
            <div class="top">
              <img :src="pic" alt="" />
              <img class="mag" :src="pic2" alt="" />
            </div>
            <div class="top">
              <img class="magT" :src="pic3" alt="" />
              <img class="magD" :src="pic4" alt="" />
            </div>
          </div>
          <!--  -->
          <div class="back-image">
            <div class="top-pic" :style="`background-image: url(${vd})`">
            <div class="icon">
              <i class="fa-sharp fa-solid fa-play fa-beat"></i>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import vp1 from "../assets/vp1.jpg";
import vp2 from "../assets/vp2.jpg";
import vp3 from "../assets/vp3.jpg";
import vp4 from "../assets/vp4.jpg";
import video from "../assets/video1.jpg";

export default {
  name: "AboutPage",
  components: {},
  data() {
    return {
      pic: vp1,
      pic2: vp2,
      pic3: vp3,
      pic4: vp4,
      vd: video,
    };
  },
  methods: {},
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/AboutePage";
</style>
