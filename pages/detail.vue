<template>
    <div class="background-all">
        <navbar2 />
        <jumbotron3 />
        <snapshot/>
        <footers/>
    </div>

</template>

<script>
import navbar2 from '~/components/navbar2.vue'
import jumbotron3 from '~/components/jumbotron3.vue'
import snapshot from '~/components/snapshot.vue'
import footers from '~/components/footers.vue'

export default {
  name: "IndexPage",
  components: { navbar2, jumbotron3, snapshot, footers}
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
