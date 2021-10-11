<template>
  <div id="app">
    <div class="container">
      <home />
    </div>
  </div>
</template>

<script>
import Home from '@/components/home/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
  body {
    font-family: 'Cousine', monospace;
  }
</style>
