<template>
  <div class="container m-auto py-10 px-36">
    <h2 class="pt-10 text-4xl text-white font-bold mb-10 display-5 text-center">Certification</h2>
    <VueSlickCarousel class="pb-10" :arrows="true" :dots="true" :autoplay="true" :speed="1000" :autoplaySpeed="2000" :slidesToShow="3">
        <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
        <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
        <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
        <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
    </VueSlickCarousel>
  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script>
<style>

ul {
  list-style: none;
}

ul li::before{
    content: "\2022";
    color: white;
}
</style>