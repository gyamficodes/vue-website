<template>
  <div class="home">
   <BannerSection/>
   <AboutPage/>
   <ServicePage/>
<TapAreaPage/>

  </div>
</template>

<script>
// @ is an alias to /src
import BannerSection from '@/components/BannerSection.vue';
import AboutPage from '@/components/AboutPage.vue';
import ServicePage from '@/components/ServicePage.vue';
import TapAreaPage from '@/components/TapAreaPage.vue';

export default {
  name: 'HomeView',
  components: {
    BannerSection,
    AboutPage,
   ServicePage,
   TapAreaPage,
  }
}
</script>
