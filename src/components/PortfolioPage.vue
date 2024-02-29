<template>
  <section class="Portfolio-Content">
    <div class="container">
      <div class="Porfilo-top">
        <div class="port-context-top">
          <h5>PORTFOLIO</h5>
          <h1>Our Latest Works For <br />Your Business</h1>
          <div class="line"></div>
          <div class="card-box">
            <div
              class="card"
              :class="{ active: activePage === index }"
              v-for="(card, index) in cards"
              :key="index"
              @click.prevent="activePage = index"
            >

              <span>{{ card.cardP.text }}</span>
            </div>
          </div>
        </div>
      </div>
      <div class="Porfilo-down">
        <div class="card-down" v-if="activePage === 0 ">
          <div
            class="image-card"
            v-for="(item, itemIndex) in loopContent"
            :key="itemIndex"
          >
            <div class="body" :style="`background-image: url(${item.img1})`">
              <div class="body-box">
                <span class="material-icons">{{ item.icon }}</span>
                <p>{{ item.text }}</p>
                <h3>{{ item.title }}</h3>
              </div>
            </div>
          </div>
        </div>


        <div class="card-down" v-if="activePage === 1 ">
          <div
            class="image-card"
            v-for="(item, itemIndex) in loopContent2"
            :key="itemIndex"
          >
            <div class="body" :style="`background-image: url(${item.img1})`">
              <div class="body-box">
                <span class="material-icons">{{ item.icon }}</span>
                <p>{{ item.text }}</p>
                <h3>{{ item.title }}</h3>
              </div>
            </div>
          </div>
        </div>

    
        <div class="card-down" v-if="activePage === 2 ">
          <div
            class="image-card"
            v-for="(item, itemIndex) in loopContent3"
            :key="itemIndex"
          >
            <div class="body" :style="`background-image: url(${item.img1})`">
              <div class="body-box">
                <span class="material-icons">{{ item.icon }}</span>
                <p>{{ item.text }}</p>
                <h3>{{ item.title }}</h3>
              </div>
            </div>
          </div>
        </div>



        <div class="card-down" v-if="activePage === 3 ">
          <div
            class="image-card"
            v-for="(item, itemIndex) in loopContent4"
            :key="itemIndex"
          >
            <div class="body" :style="`background-image: url(${item.img1})`">
              <div class="body-box">
                <span class="material-icons">{{ item.icon }}</span>
                <p>{{ item.text }}</p>
                <h3>{{ item.title }}</h3>
              </div>
            </div>
          </div>
        </div>

        <div class="card-down" v-if="activePage === 4 ">
          <div
            class="image-card"
            v-for="(item, itemIndex) in loopContent5"
            :key="itemIndex"
          >
            <div class="body" :style="`background-image: url(${item.img1})`">
              <div class="body-box">
                <span class="material-icons">{{ item.icon }}</span>
                <p>{{ item.text }}</p>
                <h3>{{ item.title }}</h3>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>
</template>
<script>
import p1 from "../assets/p1.jpg";
import p2 from "../assets/p2.jpg";
import p3 from "../assets/p3.jpg";
import p4 from "../assets/p4.jpg";
import p5 from "../assets/p5.jpg";
import p6 from "../assets/p6.jpg";

export default {
  name: "PortfoioPage",
  components: {},
  props: [],
  data() {
    return {
      activePage: 0,
      img1: p1,
      cards: [
        {
          cardP: { text: "all works" },
        },
        {
          cardP: { text: " Branding" },
        },
        {
          cardP: { text: "Prototype" },
        },
        {
          cardP: { text: "UX Research" },
        },
        {
          cardP: { text: "Web Design" },
        },
      ],
      loopContent: [
        {
          icon: "search",
          img1: p1,
          text: "Prototype UX Research",
          title: "Digital Marketing",
        },
        {
          icon: "search",
          img1: p2,
          text: "UX Research",
          title: "Awesome Creative",
        },
        {
          icon: "search",
          img1: p3,
          text: "Design, Photoshop",
          title: "Business Solution",
        },
        {
          icon: "search",
          img1: p4,
          text: "Software Engineer",
          title: "Company Project",
        },
        {
          icon: "search",
          img1: p5,
          text: "Photoshop",
          title: "Mastering Web Design",
        },
        {
          icon: "search",
          img1: p6,
          text: "Design, Photoshop",
          title: "Awesome Logo Design",
        },
      ],

      loopContent2: [
        {
          icon: "search",
          img1: p1,
          text: "Prototype UX Research",
          title: "Digital Marketing",
        },
      
        {
          icon: "search",
          img1: p5,
          text: "Photoshop",
          title: "Mastering Web Design",
        },
        
     
      ],
      loopContent3: [
       
        {
          icon: "search",
          img1: p2,
          text: "UX Research",
          title: "Awesome Creative",
        },
        {
          icon: "search",
          img1: p3,
          text: "Design, Photoshop",
          title: "Business Solution",
        },
        {
          icon: "search",
          img1: p4,
          text: "Software Engineer",
          title: "Company Project",
        },
       
      ],
      loopContent4: [
       
        {
          icon: "search",
          img1: p4,
          text: "Software Engineer",
          title: "Company Project",
        },
       
        {
          icon: "search",
          img1: p6,
          text: "Design, Photoshop",
          title: "Awesome Logo Design",
        },
      ],
      loopContent5: [
        {
          icon: "search",
          img1: p1,
          text: "Prototype UX Research",
          title: "Digital Marketing",
        },
      
        {
          icon: "search",
          img1: p5,
          text: "Photoshop",
          title: "Mastering Web Design",
        },
        
     
      ],
    };
  },
  methods: {
    setActivePage(index) {
      this.activePage = index;
    },
  },
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/PortfolioPage";
</style>
