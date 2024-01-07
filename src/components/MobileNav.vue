<template>
  <section class="Moblie-Nav">
    <div id="nav" class="Mobile-Navbar" @click="showDropDown">
      <div class="mb-menu">
        <h1>{{ name }}</h1>
        <div class="icons-box" @click="isIconShow">
          <span v-if="iconShow" class="material-icons Icon">{{ menu }}</span>
          <span v-else class="material-icons Icon">{{ close }}</span>
        </div>
      </div>
    </div>

  

    <!--  -->
    <transition name="fade-slide">
      <div class="Mobile-Links" v-if="isShowDropDown">
         <a href="" class="link">
         <h3>home</h3>
         <span  class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>company</h3>
         <span class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>services</h3>
         <span class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>pages</h3>
         <span class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>elements</h3>
         <span class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>blog</h3>
         <span class="material-icons">add</span>
         </a>
         <a href="" class="link">
         <h3>contact</h3>
         <span class="material-icons">add</span>
         </a>

         
    </div>
  </transition>
    <!--  -->
    
  </section>
</template>


<script>
export default {
  comments: {},
  props: ['name','menu','close'],
  mixins: [],
  data() {
    return {
      iconShow: true,
      isShowDropDown: false,
    };
  },
  methods: {
    isIconShow() {
      return (this.iconShow = !this.iconShow);
    },
    showDropDown(){
      return this.isShowDropDown = !this.isShowDropDown
    }
  },
  mounted() {},
  computed:{
   
  },
  created() {},
};
</script>

<style lang="scss">
.fade-slide-enter-active,
.fade-slide-leave-active {
  transition: transform 0.5s ease-in-out; /* Change the transition properties as needed */
}

.fade-slide-enter,
.fade-slide-leave-to {
  transform: translateY(-100%); /* Initial and final state for the slide effect */
}
@import "../assets/Sass/MobileNav.scss";
</style>
