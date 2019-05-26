<template>
  <section class="section is-large">
    <navbar></navbar>
    <carousel></carousel>
    <div class="container has-text-centered">
      <b-row>
        <b-col>
          <card></card>
        </b-col>
        <b-col>
          <card></card>
        </b-col>
        <b-col>
          <card></card>
        </b-col>
      </b-row>
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