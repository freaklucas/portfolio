<template>
  <div>
    <Header />
    <About />
    <Project />
    <Tech />
    <Creates />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/template/Header.vue";
import About from "@/components/template/About.vue";
import Project from "@/components/template/Project.vue";
import Tech from "@/components/template/Tech.vue";
import Creates from "@/components/template/Creates.vue";
import Footer from "@/components/template/Footer.vue";



export default {
  name: "Home",
  components: {
    Header,
    About,
    Project,
    Tech,
    Creates,
    Footer
  },
};
</script>

<style>
</style>