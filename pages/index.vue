<template>
  <section class="section is-large">
    <div class="container has-text-centered">
      <carousel></carousel>

      <card></card>
      <card></card>
    </div>
  </section>
</template>

<script>
  import Carousel from '../components/Carousel'
  import Card from '../components/Card'
  export default {
    components: {
      Carousel,
      Card
    }
  }
</script>