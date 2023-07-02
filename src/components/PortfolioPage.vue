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
              class="card "
              :class="{ 'active': activePage === index }" 
               v-for="(card, index) in cards"
              :key="index"
              @click.prevent="activePage = index"
              @click="setActivePage"
            >
              <span>{{card.cardP.text }}</span>
            </div>
          </div>
        </div>
      </div>
      <div class="Porfilo-down">
      <div class="card-down">
         <div class="image-card" >
         <div class="body" :style="`background-image: url(${img1})`"></div>
         </div>
      </div>
      </div>
    </div>
  </section>
</template>

<script>
import p1 from '../assets/p1.jpg';

export default {
  name: "PortfoioPage",
  components: {},
  props: [],
  data() {
    return {
      activePage: 0,
      activePageIndex: 0,
      img1:p1,
      cards: [
        {
          cardP:{ text: "all works" },
        },
        {
          cardP: { text: " Branding" },
        },
        {
          cardP:{ text: "Prototype" },
        },
        {
          cardP:{ text: "UX Research" },
        },
        {
          cardP:{ text: "Web Design" },
        },
      ],
    };
  },
  methods: {
    setActivePage(index) {
    this.activePageIndex = index;
  }
  },
  mounted() {},
  computed: {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/PortfolioPage";
</style>
