<template>
   <section class="RequesstPage" :style="`background-image: url(${image})1`"></section>
</template>

<script>
import pic from '../assets/call-bg.png';
    export default {
        data(){
            return{
                image:pic,
            }
        },
        methods: {
  
  },
  mounted() {},
  computed: {},
  created() {},
    }
</script>

<style lang="scss">
@import'../assets/Sass/RequestPage';
</style>