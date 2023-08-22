<template>
  <section class="footer_Page" :style="`background-image: url(${image}) `">
    <div class="container">
     
      <div class="sub-content-page">
        <div class="sub-footer-left">
          <div class="sub-footer-leftA">
            <div class="forter-logo">
              <img :src="logo" alt="" />
            </div>
            <div class="p-text">
              <p>
                Completely strategize client-cent  <br> Phosfluorescently
              iterate efficient <br>  
                   internal or organic.
              </p>
            </div>
            <div class="fot-flex">
              <span>Follow Us</span>
              <div class="icons-flex">
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="#"><i class="fa-brands fa-skype"></i></a>
              </div>
            </div>
          </div>
          <div class="sub-footer-leftB">
            <div class="heading">
              <h3>Our Services</h3>
            </div>
            <span>
              <span class="material-icons">arrow_right_alt</span>
              Home
            </span>
            <span>
              <span class="material-icons">arrow_right_alt</span>
              About Us
            </span>
            <span>
              <span class="material-icons">arrow_right_alt</span>
              Contact Us
            </span>
            <span>
              <span class="material-icons">arrow_right_alt</span>
            Service
            </span>
            <span>
              <span class="material-icons">arrow_right_alt</span>
             Our Team
            </span>
            <span>
            <span class="material-icons">arrow_right_alt</span>
              Social Marketing
            </span>
          </div>
        </div>
        <div class="sub-footer-right">
        <div class="sub-footer-right1">
         <div class="headings"> <h3>Popular Post</h3></div>
         <div class="My-Box">
         <img :src="image2" alt="">
        <div>
        <h3>Business Strategy Plan <br> 2022 From the USA</h3>
        <p>April 9, 2023</p>
        </div>
         </div>
         <div class="lineW"></div>

        </div>
        <div class="sub-footer-right2">b</div>
        </div>
      </div>

      <div class="footer-nav">
        <div class="footer-nav-menu">
          <span>© 2023 Techno.All Rights Reserved.</span>
          <div class="links-footer">
            <a href="#">Privacy Policy</a>
            <a class="pin" href="#">/</a>
            <a href="#"> Terms & Conditions</a>
            <a :style="{marginLeft: 20 +'px'}" href="#"> contact us</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import logo from "../assets/footre-logo.png";
import footerBanner from "../assets/footer-threee.jpg";
import footerImage from "../assets/Footer-image.png" 

export default {
  name: "FooterPage",
  components: {},
  props: [],
  data() {
    return {
      logo,
     image: footerBanner,
     image2: footerImage
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss"></style>
