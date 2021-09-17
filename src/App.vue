<template>
<div id="App">
  <ciccio />
  <gen />
</div>
</template>

<script>
import ciccio from './components/ciccio.vue';
import gen from './components/gen.vue'
export default {
  name: 'App',
  components: {
    gen,
    ciccio
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>


