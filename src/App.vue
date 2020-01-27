<template>
  <div id="app-div">
    <NavBar />
    <div class="container-fluid">
      <Hero
        title="The Best Title Ever!"
        subtitle="And a darn good subtitle"
      ></Hero>
    </div>
  </div>
</template>

<script>
import Hero from './components/Hero.vue';
import NavBar from './components/NavBar';
export default {
  name: 'App',
  data: () => ({
    msg: 'Hi Mom!'
  }),
  components: {
    Hero,
    NavBar
  },
  methods: {}
};
</script>
