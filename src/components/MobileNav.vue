<template>
  <section class="Moblie-Nav">
    <div class="Mobile-Navbar">
      <div class="mb-menu">
        <h1>Techno</h1>
        <div class="icons-box" @click="isIconShow">
          <span v-if="iconShow" class="material-icons Icon">menu</span>
          <span v-else class="material-icons Icon">close</span>
        </div>
      </div>
    </div>
    <!--  -->
    <div></div>


    
    <!--  -->
  </section>
</template>

<script>
export default {
  comments: {},
  props: [],
  mixins: [],
  data() {
    return {
      iconShow: true,
    };
  },
  methods: {
    isIconShow() {
      return (this.iconShow = !this.iconShow);
    },
  },
  mounted() {},
  computed:{
   
  },
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/MobileNav.scss";
</style>
