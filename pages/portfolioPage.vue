<template>
  <div class="background-all">
      <navbar2/>
      <jumbotron2/>
      <contents/>
      <footers />
    
  </div>

</template>

<script>
import navbar2 from '~/components/navbar2.vue'
import jumbotron2 from '~/components/jumbotron2.vue'
import contents from '~/components/contents.vue'
import footers from '~/components/footers.vue'

export default {
  name: "IndexPage",
  components: { navbar2, jumbotron2, contents, footers }
}

</script>

<style>

.background-all{
  background-image: url('/bg.png');
  background-size: 100%;
}

@media screen and (max-width: 766px) {
    .background-all{
      background-image: url('/bg.png');
      background-repeat: no-repeat;
      background-size: cover;
    }
  }

</style>
