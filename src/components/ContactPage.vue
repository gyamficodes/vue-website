<template>
  <section class="ContactPage" :style="`background-image: url(${pic})`">
    <div class="contact-page-menu">
      <div class="contact">
        <ditv class="contactpage-top">
          <h4>GET QUOTE</h4>
          <h1>
            Make An <br />
            Free Consultant
          </h1>
          <div class="line"></div>
        </ditv>
        <ditv class="contactpage-down">
          <div class="input-page">
            <input type="text" placeholder="name" required />
            <input type="email" placeholder="email address" required />
          </div>
          <div class="input-page">
            <input type="number" placeholder="phone number" required />
            <input type="link" placeholder="website" required />
          </div>

          <div class="text-area">
            <textarea
              name=""
              id=""
              cols="147.9"
              placeholder="write a message"
            ></textarea>
          </div>
          <div class="btn-a">
          free consultancy
          </div>
          <!--  -->
        </ditv>
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
