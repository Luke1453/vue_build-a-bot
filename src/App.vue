<template>
  <main>
    <HomePage msg='Welcome to Your Vue.js + TypeScript App'/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HomePage from './components/HomePage.vue';

export default defineComponent({
  name: 'App',
  components: {
    HomePage,
  },
});
</script>

<style>
  body{
    background: linear-gradient(to bottom, #555, #999);
    background-attachment: fixed;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
main{
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1024px;
  min-height: 300px;
}
</style>
