<template>
  <div class="background-all">
    <navbar />
    <jumbotron />
  </div>

</template>

<script>
import navbar from '~/components/navbar.vue'
import jumbotron from '~/components/jumbotron.vue'
export default {
  name: "IndexPage",
  components: { navbar }
}
</script>

<style>
.background-all{
  background-image: url('/bg.png');
  background-size: 100%;
}
</style>
