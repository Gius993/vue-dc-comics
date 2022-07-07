<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <PageHeader />
    <PageMain  />
    <PageFooter />
  </div>
</template>

<script>
   import PageHeader from "./components/PageHeader.vue";
   import PageMain from "./components/PageMain.vue";
   import PageFooter from "./components/PageFooter.vue"
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components:{
    PageHeader,  
    PageMain,
    PageFooter    
}

}
</script>

<style lang="scss">
  @import './style/common.scss';
  @import  './style/variables.scss';
</style>
