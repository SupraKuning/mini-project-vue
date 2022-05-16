<template>
  <div class="background-all">
    <navbar />
    <jumbotron />
    <experience />
    <skill />
    <certification />
    <card />
    <footers />
  </div>

</template>

<script>
import navbar from '~/components/navbar.vue'
import jumbotron from '~/components/jumbotron.vue'
import experience from '~/components/experience.vue'
import skill from '~/components/skill.vue'
import certification from '~/components/certification.vue'
import card from '~/components/card.vue'
import footers from '~/components/footers.vue'

export default {
  name: "IndexPage",
  components: { navbar, jumbotron, experience, skill, certification, card, footers }
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
