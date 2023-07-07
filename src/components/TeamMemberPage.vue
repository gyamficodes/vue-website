<template>
  <section class="TeamMemberPage">
    <div class="Team-top">
      <div class="team-top-content">
        <h6>TEAM MEMBER</h6>
        <h1>
          Our Awesome Creative <br />
          Team Member
        </h1>
        <div class="line"></div>
      </div>
    </div>
    <div class="Team-down">
      <div class="Team-cards">
        <div class="cards">
          <div class="card-image" :style="`background-image: url(${pic}) `">
            <div class="links">
              <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
              <a href="#"><i class="fa-brands fa-twitter"></i></a>
              <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
              <a href="#"><i class="fa-brands fa-pinterest"></i></a>
            </div>
          </div>
          <div class="card-text"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import image from "../assets/team1.jpg";
export default {
  name: "TeamMemberPage",
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
@import "../assets/Sass/TeamMemberPage";
</style>
