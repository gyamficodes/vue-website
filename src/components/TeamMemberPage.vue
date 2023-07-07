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
        <div class="cards" v-for="card in cards" :key="card.id">
          <div class="card-image" :style="`background-image: url(${card.pic}) `">
            <div class="links">
              <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
              <a href="#"><i class="fa-brands fa-twitter"></i></a>
              <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
              <a href="#"><i class="fa-brands fa-pinterest"></i></a>
            </div>
          </div>
          <div class="card-text">
           <h4>{{ card.name }}</h4>
             <p>{{ card.title }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import image from "../assets/team1.jpg";
import image2 from "../assets/team2.jpg";
import image3 from "../assets/team3.jpg";
export default {
  name: "TeamMemberPage",
  components: {},
  props: [],
  data() {
    return {
      cards:[
        {
          id:1,
          pic:image,
          name:'David Malaan',
          title:'CEO'
        },
        {
          id:2,
          pic:image2,
          name:'Andres Jhohne',
          title:'DIRECTOR'
        },
        {
          id:3,
          pic:image3,
          name:'Michel Balak',
          title:'FOUNDER'
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
@import "../assets/Sass/TeamMemberPage";
</style>
