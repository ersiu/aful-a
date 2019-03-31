<template>
  <div id="app">
    <navBar />
    <!-- <router-view/> -->
    <home />

  </div>
</template>

<script>
  import navBar from '@/components/NavBar.vue'
  import home from './views/Home.vue'

  export default {
    name: 'app',
    components: {
      navBar,
      home
    }
  }
</script>

<style>
  body {
    background: #333;
    color: #ffffff;
    /* padding-top: 70px; */
  }
  

</style>
