<template>
  <div class="home">
    <Header />
    <Hero />
    <WomanBanner />
    <InstaBanner />
    <Partner />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import WomanBanner from "@/components/WomanBanner.vue";
import InstaBanner from "@/components/InstaBanner.vue";
import Partner from "@/components/Partner.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    WomanBanner,
    InstaBanner,
    Partner,
    Footer,
  },
};
</script>
