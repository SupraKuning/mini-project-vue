<template>
  <div class="container m-auto py-5 px-10">
    <h2 class="pt-10 text-4xl text-white font-bold mb-10 display-5" data-aos="fade-right">
      Snapshot.
    </h2>
    <!-- <VueSlickCarousel class="pb-10" :arrows="true" :dots="true" :autoplay="true" :speed="1000" :autoplaySpeed="2000" :slidesToShow="3"> -->
    <VueSlickCarousel class="pb-10" v-bind="settings">
      <img class="p-5 m-auto" data-aos="fade-down" src="/n1.jpg" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n2.jpg" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n3.png" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n4.png" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n5.png" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n6.png" alt="" />
      <img class="p-5 m-auto" data-aos="fade-down" src="/n7.jpg" alt="" />
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
    data() {
    return {
      settings: {
        dots: true,
        infinite: true,
        autoplay: true,
        speed: 2000,
        autoplaySpeed: 1000,
        slidesToShow: 5,
        slidesToScroll: 5,
        initialSlide: 0,
        responsive: [
          {
            breakpoint: 1024,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              infinite: true,
              dots: true,
            },
          },
          {
            breakpoint: 600,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
              initialSlide: 1,
            },
          },
          {
            breakpoint: 480,
            settings: {
              slidesToShow: 1,
              slidesToScroll: 1,
            },
          },
        ],
      },
    };
  },
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