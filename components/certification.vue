<template>
  <div class="container m-auto py-10 px-20 md:px-36">
    <h2 class="pt-10 text-4xl text-white font-bold mb-10 display-5 text-center" data-aos="fade-left">
      Certification
    </h2>
    <!-- <VueSlickCarousel class="pb-10" :arrows="true" :dots="true" :autoplay="true" :speed="1000" :autoplaySpeed="2000" :slidesToShow="3"> -->
    <VueSlickCarousel class="pb-10" v-bind="settings">
      <img class="rounded-t-lg p-5 m-auto" src="/ser1.png" alt="" />
      <img class="rounded-t-lg p-5 m-auto" src="/ser2.png" alt="" />
      <img class="rounded-t-lg p-5 m-auto" src="/ser3.png" alt="" />
      <img class="rounded-t-lg p-5 m-auto" src="/ser4.png" alt="" />
      <img class="rounded-t-lg p-5 m-auto" src="/ser5.png" alt="" />
    </VueSlickCarousel>
  </div>
</template>

<script>
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";

export default {
  name: "MyComponent",
  components: { VueSlickCarousel },
  data() {
    return {
      settings: {
        dots: true,
        infinite: true,
        autoplay: true,
        speed: 4000,
        autoplaySpeed: 2000,
        slidesToShow: 3,
        slidesToScroll: 3,
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
};
</script>
<style>
.slick-dots {
  list-style: none;
}

.slick-dots li::before {
  content: "\2022";
  color: white;
}
</style>
