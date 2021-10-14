<template>
  <div>
    <particles-bg type="cobweb" :bg="true" />
    <Header />
    <About />
    <Project />
    <Tech />
    <Creates />
  </div>
</template>

<script>
import Header from "@/components/template/Header.vue";
import About from "@/components/template/About.vue";
import Project from "@/components/template/Project.vue";
import Tech from "@/components/template/Tech.vue";
import Creates from "@/components/template/Creates.vue";

import { ParticlesBg } from "particles-bg-vue";


export default {
  name: "Home",
  components: {
    Header,
    About,
    Project,
    Tech,
    Creates,
    ParticlesBg
  },
};
</script>

<style>
</style>