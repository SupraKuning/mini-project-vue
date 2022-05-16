<template>
    <div class="container my-24 px-6 mx-auto">
        <h1 class="font-black text-white text-5xl mb-10">
            Snapshot.
        </h1>
        <VueSlickCarousel class="pb-10" :arrows="true" :dots="true" :autoplay="true" :speed="1000" :autoplaySpeed="2000" :slidesToShow="5">
            <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
            <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
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