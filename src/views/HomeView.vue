<template>
  <div class="home">
   <BannerSection/>
  </div>
</template>

<script>
// @ is an alias to /src
import BannerSection from '@/components/BannerSection.vue';

export default {
  name: 'HomeView',
  components: {
    BannerSection,
  }
}
</script>
