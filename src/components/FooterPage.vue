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
              <span  class="material-icons">arrow_right_alt</span>
              Home
            </span>
            <span>
              <span  class="material-icons">arrow_right_alt</span>
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
            <img :src="image2" alt="Avatar">
        <div>
        <h3>Business Strategy Plan <br> 2022 From the USA</h3>
        <p>April 9, 2023</p>
        </div>
         </div>
         <div class="lineW"></div>
         <div class="My-Box">
         <img :src="pic" alt="Avatar">
        <div>
        <h3>The Most 10 Chrome <br>  Extention Download <br>  Strategy</h3>
        <p>April 9, 2023</p>
        </div>
         </div>
        </div>
        <div class="sub-footer-right2">
        <h3 >Contact Info</h3>
           <div class="right2-flex">
           <div class="icon-flex"><span class="material-icons">location_on</span></div>
           <div class="icon-text">
           <h2>Location</h2>
           <p>55 Main Street, New York.</p>
           </div>
           </div>


           <div class="right2-flex">
           <div class="icon-flex"><span class="material-icons">email</span></div>
           <div class="icon-text">
           <h2>Email Us</h2>
           <p>example@gmail.com</p>
           </div>
           </div>
           
           <div class="right2-flex">
           <div class="icon-flex"><span class="material-icons">phone</span></div>
           <div class="icon-text">
           <h2>Phone Us</h2>
           <p>+012 (345) 678 99</p>
           </div>
           </div>

        </div>
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
import footerImage2 from "../assets//footer-image2.png" 

export default {
  name: "FooterPage",
  components: {},
  props: [],
  data() {
    return {
      logo,
     image: footerBanner,
     image2: footerImage,
     pic:footerImage2
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss"></style>
