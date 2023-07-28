<template>
  <section class="footer_Page">
    <div class="container">
      <div class="Subscribe-Page">
        <div class="sub-page-text">
          <h2>Subscribe Our Newsletter</h2>
          <div class="box-sub">
            <input type="email" placeholder="ener your email" />
            <div class="btnA">
              <span>Subscribe</span>
            </div>
          </div>
        </div>
      </div>
      <div class="sub-content-page">
        <div class="sub-footer-left">
          <div class="sub-footer-leftA">
            <div class="forter-logo">
              <img :src="logo" alt="" />
            </div>
            <div class="p-text">
              <p>
                Condimentum rhoncus, sem quam <br />
                semper libero, sit amet adipiscing <br />
                sem neque sed ipsum. Nam quam nunc, <br />
                blandit vel, luctus.
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
            <span
              ><p></p>
              Marketing Strategy
            </span>
            <span
              ><p></p>
              Interior Design
            </span>
            <span
              ><p></p>
              Digital Services
            </span>
            <span
              ><p></p>
              Product Selling
            </span>
            <span
              ><p></p>
              Product Design
            </span>
            <span
              ><p></p>
              Social Marketing
            </span>
          </div>
        </div>
        <div class="sub-footer-right">dsgfeht</div>
      </div>

      <div class="footer-nav">
        <div class="footer-nav-menu">
          <span>© 2023 Techno.All Rights Reserved.</span>
          <div class="links-footer">
            <a href="#">Privacy Policy</a>
            <a class="pin" href="#">/</a>
            <a href="#"> Terms & Conditions</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import logo from "../assets/footre-logo.png";

export default {
  name: "FooterPage",
  components: {},
  props: [],
  data() {
    return {
      logo,
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss"></style>
