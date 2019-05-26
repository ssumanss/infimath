<template>
  <section class="section is-large">
    <navbar></navbar>
    <div class="container has-text-centered">
      <jumbotron></jumbotron>
<b-container class="bv-example-row">
  <b-row>
    <b-col cols="8">
      col-8 
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Neque, distinctio officiis, praesentium debitis placeat dicta laboriosam, id quibusdam perferendis delectus illum sunt. Provident illum laborum repudiandae dignissimos facilis, eveniet nihil!</p>
    </b-col>
    <b-col cols="4">
      col-4 
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias illo error provident aut explicabo nemo sunt vel dignissimos nisi nam sequi quidem, aspernatur temporibus fugiat amet voluptas odio, reiciendis soluta.</p>
    </b-col>
  </b-row>
</b-container>
    </div>
  </section>
</template>

<script>
  import Jumbotron from '../components/Jumbotron'
  import Navbar from '../components/Navbar'
  export default {
    components: {
      Jumbotron,
      Navbar
    }
  }
</script>