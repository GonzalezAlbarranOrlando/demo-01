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
  /*Font Awesome Web Application Icons */
  @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css';
  /*My css file(s)*/
  @import '@/assets/css/styles.css';
</style>
  
