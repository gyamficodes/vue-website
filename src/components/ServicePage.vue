<template>
  <section class="service-page-content">
    <div class="container">
      <div class="service-text">
        <div class="text-card">
          <div class="card" v-for="card in cards" :key="card.id">
            <div class="num">
              <span>{{ card.number }}</span>
              <div class="wt"></div>
            </div>
            <div class="text">
              <h3>{{ card.title }}</h3>
              <p>{{ card.message }}</p>
              <span>{{ card.details }} <i class="fa-solid fa-arrow-right"></i></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ServicePage',
  components: {},
  data() {
    return {
      cards: [
        {
          id: 1,
          number:"01",
          title:'Marketing Strategy & Analysis',
          message:'Whether bringing new amazing products and services to market discovering new ways to make mature',
          details:'read more'
        },
        {
          id: 2,
          number:"02",
          title:'Web Design & Development',
          message:'Whether bringing new amazing products and services to market discovering new ways to make mature',
          details:'read more'
        },
        {
          id: 3,
          number:"03",
          title:'SEO & Digital Marketing',
          message:'Whether bringing new amazing products and services to market discovering new ways to make mature',
          details:'read more'
        },
        
      ]
    }
  },
  methods: {},
  mounted() { },
  computed: {},
  created() { },
}
</script>

<style lang="scss">@import'../assets/Sass/ServicePage';</style>