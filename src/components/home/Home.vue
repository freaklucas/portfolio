<template>
  <div>
    <Header />
    <About />
    <Project />
    <Tech />
  </div>
</template>

<script>
import Header from "@/components/template/Header.vue";
import About from "@/components/template/About.vue";
import Project from "@/components/template/Project.vue";
import Tech from "@/components/template/Tech.vue";

export default {
  name: "Home",
  components: {
    Header,
    About,
    Project,
    Tech
  },
};
</script>

<style>
</style>