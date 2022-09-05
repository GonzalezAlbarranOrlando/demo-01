<template>
  <MyHeader/>    
  <router-view></router-view>
  <MyFooter/>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';

export default {
name: 'App',
components: { MyHeader, MyFooter}
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
