<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Input />
  </div>
</template>

<script>
import Input from './components/Input.vue'

export default {
  name: 'App',
  components: {
   Input 
  }
}
</script>

<style >
@import "~bulma";
@import "../node_modules/bulma/sass/utilities/_all.sass";
@import "../node_modules/bulma/sass/base/_all.sass";
@import "../node_modules/bulma/sass/utilities/_all.sass";
@import "../node_modules/bulma/sass/elements/_all.sass";
@import "../node_modules/bulma/sass/form/_all.sass";
@import "../node_modules/bulma/sass/components/_all.sass";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
