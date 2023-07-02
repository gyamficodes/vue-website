<template>
  <section class="sub-page">
    <div class="container">
      <div class="main-box-sub">
        <div class="sub-content">
          <div class="card-item-box">
          <!-- main card -->
            <a class="card " 
            :class="{'active': activePage === index}"
            @click="activePageIndex"
            @click.prevent="activePage = index"
            :href="page.card.url" v-for="(page,index) in pages" :key="index" >
              <span class="material-icons">{{ page.card.icon }}</span>
              <h4>{{ page.card.text }}</h4>
            </a>
          </div>
        </div>
      </div>
      <div class="card-body">
      <!-- card-page -->
        <div class="card-left">
          <img :src="pages[activePage].image" alt="" />
        </div>
        <div class="card-right">
          <h4>{{ pages[activePage].text }}</h4>
          <p>{{ pages[activePage].pageT }}</p>
          <p>{{ pages[activePage].pageTT }}</p>
          <div class="flb">
            <span><i class="fa-solid fa-arrow-right"></i>{{ pages[activePage].row }}</span>
            <span><i class="fa-solid fa-arrow-right"></i> {{ pages[activePage].row }}</span>
            <span><i class="fa-solid fa-arrow-right"></i> {{ pages[activePage].row }}</span>
          </div>
          <div class="buttons">
          <div class="btnA">
          <span>get a quote</span>
          <i class="fa-solid fa-arrow-right"></i>
          </div>
          <div class="btnB">
          <span>get a quote</span>
          <i class="fa-solid fa-arrow-right"></i>
          </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import tab1 from '../assets/tab1.jpg';
import tab2 from '../assets/tab2.jpg';
import tab3 from '../assets/tab3.jpg';
import tab4 from '../assets/tab1.jpg';

export default {
  name: "SubPage",
  data() {
    return {
      activePage: 0,
       activePageIndex: 0,
      pages: [
        {
         card:{text:'Digital Marketing',icon: 'laptop_mac' ,url:'page1.html'},
         pageT: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusm   tempor  incididunt ut labore et dolore magna aliqua. Ut enim advis  minim veniam,  quis nostrud exercitat ullamco But I must explain to      you how all this  mistaken idea of denouncing",
         row:'Appropriately empower dynamic leadershp',
         image: tab1,
         text:'Digital Marketing',
         pageTT:' Porem tpsum dolor sit amet, consectetur adipisicing elit, sed eiusm morem wpsum solor sit amet, consectetur adipisicing elit, sed eiusm tempor incididunt ut labore et dolore magna',
        },
        {
         card:{text:'Web Hosting Provide',icon: 'laptop_mac',url:'page2.html'},
         pageT: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusm   tempor  incididunt ut labore et dolore magna aliqua. Ut enim advis  minim veniam,  quis nostrud exercitat ullamco But I must explain to      you how all this mistaken idea of denouncing",
        row: ' Globally myocardinate interactive supply chains',
        image: tab2,
        text:'Web Hosting Provide',
        pageTT:' Porem tpsum dolor sit amet, consectetur adipisicing elit, sed eiusm morem wpsum solor sit amet, consectetur adipisicing elit, sed eiusm tempor incididunt ut labore et dolore magna',

        },
        {
         card:{text:'Data Server Security',icon: 'databasee',url:'page3.html'},
         pageT: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusm   tempor  incididunt ut labore et dolore magna aliqua. Ut enim advis  minim veniam,  quis nostrud exercitat ullamco But I must explain to      you how all this  mistaken idea of denouncing",
         row: 'Globally revolutionize global sources through',
         image: tab4,
         text:'Data Server Security',
         pageTT:' Porem tpsum dolor sit amet, consectetur adipisicing elit, sed eiusm morem wpsum solor sit amet, consectetur adipisicing elit, sed eiusm tempor incididunt ut labore et dolore magna',

        },

        {
         card:{text:'Web Design Development',icon: 'code',url:'page4.html'},
         pageT: "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusm   tempor  incididunt ut labore et dolore magna aliqua. Ut enim advis  minim veniam,  quis nostrud exercitat ullamco But I must explain to      you how all this mistaken idea of denouncing",
         row: 'Globally revolutionize global sources through',
         image: tab3,
         text:'Web Design & Development',
         pageTT:' Porem tpsum dolor sit amet, consectetur adipisicing elit, sed eiusm morem wpsum solor sit amet, consectetur adipisicing elit, sed eiusm tempor incididunt ut labore et dolore magna',

        },

      ],
    };
  },
  methods: {
    setActivePage(index){
      this.activePageIndex = index;
    }
  },
  mounted() { },
  computed: {},
  created() { },
};
</script>

<style lang="scss">
@import "../assets/Sass/subPage";

</style>
