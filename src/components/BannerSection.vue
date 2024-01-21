<template>
    <section class="banner-page" :style="`background-image: url(${background});`">
        <BannerNav/>
        <section class="banner-content">
            <div class="container">
                <div class="content-menu">
                    <div class="content-text">
                        <h1>We Provide The Best
                            <br> All Kind IT Solution
                        </h1>
                        <p>Morem upsum dolor set amet, consectetur adipisicing elit, sed do eiusmod  <br> incididunt
                          laboret dolore magna aliqua.
                        </p>
                        <div class="box">

                            <div class="nav-btn">
                                <span>how it work <i class="fa-solid fa-arrow-right-long fa-beat"></i></span>
                            </div>
                            <div class="btn">
                                <i class="fa-solid fa-play"></i></div>
                        </div>
                    </div>
                    <div class="content-image">
                        <img class="anima" :src="anima" alt="">
                        <img class="pic" :src="shape" alt="">
                    </div>
                </div>
            </div>
        </section>
    </section>
</template>


<script>
import baner from '../assets/slider-3.png';
import BannerNav from './BannerNav.vue';
import round from '../assets/sdt.png';
import pic from '../assets//shape1.png';

export default {
    name: 'BannerSection',
    components: {
        BannerNav
    },
    data() {
        return {
            background: baner,
            anima: round,
            shape:  pic,
        }
    },
    methods: {},
    mounted() { },
    computed: {},
    created() { },
}
</script>

<style lang="scss">
@import'../assets/Sass/BannerSec';
</style>