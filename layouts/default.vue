<template>
  <div>
    <navbar></navbar>
    <nuxt/>
  </div>
</template>
<script>
  import Navbar from '../components/Navbar'
  import Jumbotron from '../components/Jumbotron'
  export default {
    components: {
      Navbar,
      Jumbotron
    }
  }
</script>
<style>
  html { font-family: Arial, sans-serif;}
</style>