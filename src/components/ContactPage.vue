<template>
  <section
    class="ContactPage"
    :style="`background-image: url(${pic})`"
  ></section>
</template>

<script>
import image from "../assets/bg-cnt.jpg";
export default {
  name: "ContactPage",
  components: {},
  props: [],
  data() {
    return {
      pic: image,
    };
  },
  methods: {},
  computed: {},
  mountedc() {},
  created() {},
};
</script>

<style lang="scss">
@import "../assets/Sass/ContactPage";
</style>
