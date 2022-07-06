<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    
  <PageHeader />
 
  </div>
</template>

<script>
   import PageHeader from "./components/PageHeader.vue";
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components:{
    PageHeader
}
}
</script>

<style lang="scss">
  @import './style/common.scss';
  @import  './style/variables.scss';
</style>
