<template>
  <Docs/>
</template>

<script>
import Docs from './components/views/docs/docs.component.vue';

export default {
  name: 'App',
  components: {
    Docs
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
