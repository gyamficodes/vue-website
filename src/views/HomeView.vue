<template>
  <div class="home">
    <BannerSection />
    <AboutPage />
    <ServicePage />
    <TapAreaPage />
    <SubPageVue />
    <ChooseUsPage/>
    <PortfolioPage/>
    <ContactPageVue/>
    <TeamMemberPage/>
    <RequestPage/>
    <BlogPage/>
    <SubscribePageVue/>
    <FooterPage/>
  </div>
</template>




<script>
// @ is an alias to /src
import BannerSection from "@/components/BannerSection.vue";
import AboutPage from "@/components/AboutPage.vue";
import ServicePage from "@/components/ServicePage.vue";
import TapAreaPage from "@/components/TapAreaPage.vue";
import SubPageVue from "@/components/SubPage.vue";
import ChooseUsPage from "@/components/ChooseUsPage.vue";
import PortfolioPage from "@/components/PortfolioPage.vue";
import ContactPageVue from "@/components/ContactPage.vue";
import TeamMemberPage from "@/components/TeamMemberPage.vue";
import RequestPage from "@/components/RequestPage.vue";
import BlogPage from "@/components/BlogPage.vue";
import FooterPage from "@/components/FooterPage.vue";
import SubscribePageVue from "@/components/SubscribePage.vue";

export default {
  name: "HomeView",
  components: {
    BannerSection,
    AboutPage,
    ServicePage,
    TapAreaPage,
    SubPageVue,
    ChooseUsPage,
    PortfolioPage,
    ContactPageVue,
    TeamMemberPage,
    RequestPage,
    BlogPage,
    FooterPage,
    SubscribePageVue,
  },
};
</script>
