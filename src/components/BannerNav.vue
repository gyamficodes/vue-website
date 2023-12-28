<template>
  <div class="nav">
    <div class="container">
     <!-- nav-menu scroll -->
     <div class="nav-menuB" v-if="isScroll">
        <div class="nav-left">
          <div class="logo">
            <img :src="image2" alt="" />
          </div>
        </div>
        <div class="nav-right">
          <div class="right-box">
            <ul>
              <li><a href="#">home</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li><a href="#">Company</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">it solutions</a></li>
                          <li><a href="#">element</a></li>
                          <li><a href="#">contact</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>
              </li>
              <li><a href="#">company</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developer</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>

              </li>
              <li><a href="#">service</a>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">company </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developer</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>

              </li>
              <li><a href="#">it solutions</a><i class="fa-sharp fa-solid fa-chevron-down"></i></li>
              <li><a href="#">element</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developer</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>
              </li>
              <li><a href="#">blog</a><i class="fa-sharp fa-solid fa-chevron-down"></i></li>
              <li style="display: flex; align-items: center; color:#fff; gap:0.2em; cursor:pointer;"><a href="#">contact</a><span class="material-icons">phone</span></li>
            </ul>
            <div class="nav-btn">
              <span>get a quote</span>
            </div>
          </div>
        </div>
      </div>
  <!-- nav-menu scroll -->


     <div class="nav-menu" v-else>
        <div class="nav-left">
          <div class="logo">
            <img :src="image" alt="" />
          </div>
        </div>
        <div class="nav-right">
          <div class="right-box">
            <ul>
              <li><a href="#">home</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li><a href="#">Company</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">it solutions</a></li>
                          <li><a href="#">element</a></li>
                          <li><a href="#">contact</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>
              </li>
              <li><a href="#">company</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developer</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>

              </li>
              <li><a href="#">service</a>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">company </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developer</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">element</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>

              </li>
              <li><a href="#">it solutions</a><i class="fa-sharp fa-solid fa-chevron-down"></i></li>
              <li><a href="#">element</a><i class="fa-sharp fa-solid fa-chevron-down"></i>
                <div class="sub-menu">
                  <ul>
                    <li class="tt"><a href="#">home</a></li>
                    <li><a href="#">Service </a><i class="fa-sharp fa-solid fa-chevron-left"></i>
                      <div class="sub-menu1">
                        <ul>
                          <li><a href="#">web designer</a></li>
                          <li><a href="#">developers</a></li>
                          <li><a href="#"> manager</a></li>
                        </ul>
                      </div>
                    </li>
                    <li><a href="#">it solutions</a></li>
                    <li><a href="#">Blog</a></li>
                    <li><a href="#">contact</a></li>
                  </ul>
                </div>
              </li>
              <li><a href="#">blog</a><i class="fa-sharp fa-solid fa-chevron-down"></i></li>
              <li style="display: flex; align-items: center; color:#fff; gap:0.2em; cursor:pointer;"><a href="#">contact</a><span class="material-icons">phone</span></li>
            </ul>
            <div class="nav-btn">
              <span>get a quote</span>
        
            </div>
          </div>
        </div>
      </div> -->
    </div>
  </div>
</template>


<script>
import logo from "../assets/log.png";
import mainLogo from "../assets/scroll-logo.png";
export default {
  name: "BannerNav",
  components: {},
  data() {
    return {
      image: logo,
      image2: mainLogo,
      isScroll: false,
    };
  },
  created(){
      window.addEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleScroll(){    
      const scrollPosition = window.scrollY;
      const scroll = scrollPosition.toFixed(0);
      const navItem = document.querySelector('.nav');
      if(scroll >= 100){
          navItem.style.position = 'fixed';
          navItem.style.top = 0;
          navItem.style.left = 0;
          navItem.style.right = 0;
          navItem.style.bottom = 0;
          navItem.style.zIndex = 999999;
          navItem.style.background = '#fff';
          navItem.style.boxShadow = '0px 2px 5px #ccc';
         this.isScroll = true
      }
      if(scroll == 0){
        navItem.style.position = 'relative';
        navItem.style.background = 'transparent';
        navItem.style.boxShadow = 'none';

        this.isScroll = false
      }
    }
  },
  mounted() { },
  computed: {},
  // created() { },
};
</script>

<style lang="scss">
@import "../assets/Sass/BannerNav";
</style>


