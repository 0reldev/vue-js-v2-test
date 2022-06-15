<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TextInterpolation message="Voici un message personnalisé réactif."/>
    <SimpleVBind message="Voici un message personnalisé réactif."/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import TextInterpolation from './components/TextInterpolation.vue';
import SimpleVBind from './components/SimpleVBind.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    TextInterpolation,
    SimpleVBind
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
