<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <PageHeader />
    <PageMain  />
    <PageFooter />
    <PageBottom />

  </div>
</template>

<script>
   import PageHeader from "./components/PageHeader.vue";
   import PageMain from "./components/PageMain.vue";
   import PageFooter from "./components/PageFooter.vue"
   import PageBottom from "./components/PageBottom.vue"
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components:{
    PageHeader,  
    PageMain,
    PageFooter,
    PageBottom    
}

}
</script>

<style lang="scss">
  @import './style/common.scss';
  @import  './style/variables.scss';
</style>
