<template>
  <section class="header">
    <div class="row jumbotron">
      <div class="col text-center">
        <h1 class="display-2">{{ title }}</h1>
        <h3 class="display-5">{{ subtitle }}</h3>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
  data: () => ({}),
  methods: {},
  props: ['title', 'subtitle']
};
</script>

<style scoped>
.jumbotron {
  border-radius: 0;
}
</style>
