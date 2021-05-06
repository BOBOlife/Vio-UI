<template>
  <div>导航栏 |
    <router-link to="/">Frank</router-link> |
    <router-link to="/xxx">Frank2</router-link>
  </div>
  <hr />
  <router-view />
</template>

<script lang="ts">
import {defineComponent} from 'vue';
import Hello from './components/Hello.vue';

export default defineComponent({
  name: 'App',
});
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
