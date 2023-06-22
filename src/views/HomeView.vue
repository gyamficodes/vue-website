<template>
  <div class="home">
   <BannerSection/>
   <AboutPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import BannerSection from '@/components/BannerSection.vue';
import AboutPage from '@/components/AboutPage.vue';

export default {
  name: 'HomeView',
  components: {
    BannerSection,
    AboutPage
  }
}
</script>
