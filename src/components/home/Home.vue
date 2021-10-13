<template>
  <div>
    <Header />
    <About />
    <Project />
  </div>
</template>

<script>
import Header from "@/components/template/Header.vue";
import About from "@/components/template/About.vue";
import Project from "@/components/template/Project.vue";

export default {
  name: "Home",
  components: {
    Header,
    About,
    Project,
  },
};
</script>

<style>
</style>