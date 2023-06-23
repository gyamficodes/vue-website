<template>
  <div class="home">
   <BannerSection/>
   <AboutPage/>
   <ServicePage/>
  </div>
</template>

<script>
// @ is an alias to /src
import BannerSection from '@/components/BannerSection.vue';
import AboutPage from '@/components/AboutPage.vue';
import ServicePage from '@/components/ServicePage.vue';

export default {
  name: 'HomeView',
  components: {
    BannerSection,
    AboutPage,
   ServicePage,
  }
}
</script>
