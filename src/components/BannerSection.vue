<template>
   <section class="banner-page" :style="`background: url(${background});`">
<BannerNav/>
   </section>
</template>

<script>
import baner from '../assets/slider-3.png';
import BannerNav from './BannerNav.vue';

    export default {
        name:'BannerSection',
        components:{
            BannerNav
        },
        data(){
            return{
                background:baner,
            }
        },
        methods:{},
        mounted(){},
        computed:{},
        created(){},
    }
</script>

<style lang="scss">
 @import'../assets/Sass/BannerSec';
</style>