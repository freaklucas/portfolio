<template>
  <div id="app">
      <particles-bg type="cobweb" :bg="true" />
      <home />
  </div>
</template>

<script>
import Home from '@/components/home/Home.vue'
import { ParticlesBg } from "particles-bg-vue";

export default {
  name: 'App',
  components: {
    ParticlesBg,
    Home,
  }
}
</script>

<style>
  body {
    font-family: 'Cousine', monospace;
  }
</style>
