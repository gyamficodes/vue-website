<template>
  <section class="Blog-Page">
    <div class="container">
      <div class="box">
        <div class="content" v-for="item in numbers" :key="item.id">
          <h1>{{ item.num }}</h1>
          <h3>{{ item.text }}</h3>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "BlogPage",
  components: {},
  props: [],
  data() {
    return {
      numbers: [
        {
          id: 1,
          num: "15K",
          text: "Happy Clients",
        },
        {
          id: 1,
          num: "1280+",
          text: "Account Number",
        },
        {
          id: 1,
          num: "10K",
          text: "Finished Projects",
        },
        {
          id: 1,
          num: "992+",
          text: "Win Awards",
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
@import "../assets/Sass/BlogPage";
</style>
