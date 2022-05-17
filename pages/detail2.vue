<template>
    <div class="background-all">
        <navbar2 />
        <jumbotron4 />
        <snapshot2/>
        <footers/>
    </div>

</template>

<script>
import AOS from 'aos'
import 'aos/dist/aos.css'

import navbar2 from '~/components/navbar2.vue'
import jumbotron4 from '~/components/jumbotron4.vue'
import snapshot2 from '~/components/snapshot2.vue'
import footers from '~/components/footers.vue'

export default {
    mounted() {
    AOS.init({ })
  },
  name: "IndexPage",
  components: { navbar2, jumbotron4, snapshot2, footers}
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
*{
  font-family: 'Montserrat', sans-serif;
}

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
