<template>
  <div id="app">
    <h1>Welcome to MedDocs</h1>
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
});
</script>

<style>
#app {
  text-align: center;
  padding: 20px;
}
</style>