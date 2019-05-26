<template>
  <section class="section is-large">
    <navbar></navbar>
    <div class="container has-text-centered">
      <carousel></carousel>

      <card></card>
      <card></card>
    </div>
  </section>
</template>

<script>
  import Navbar from '../components/Navbar'
  import Carousel from '../components/Carousel'
  import Card from '../components/Card'
  export default {
    components: {
      Navbar,
      Carousel,
      Card
    }
  }
</script>