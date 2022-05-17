<template>
    <div class="container my-24 px-6 mx-auto">

  <!-- Section: Design Block -->
  <section class="mb-32 text-gray-800 text-center lg:text-left">
    <style>
      @media (min-width: 992px) {
        .rotate-lg-6 {
          transform: rotate(6deg);
        }
      }

      /* These are the KEY styles - you can add them directly to any object you want in your project */
      .fancy-border-radius {
        border-radius: 53% 47% 52% 48% / 36% 41% 59% 64%;
      }
    </style>

    <!-- Jumbotron -->
    <div class="container mx-auto xl:px-32 text-center lg:text-left">
      <div class="grid lg:grid-cols-2 flex items-center">
        <div class="mb-12 lg:mb-0">
          <div
            class="relative block rounded-lg shadow-2xl px-6 py-12 md:px-12 lg:-mr-14"
           
          >
            <h2 class="text-5xl text-white font-black mb-5 display-5">Hello, i'm Gavriel</h2>
            <p class="text-white font-semibold mt-7 mb-2">
                Graphic Designer, UI/UX Designer & Video Editor
            </p>
            <p class="mb-10 text-white font-extralight">
             I am an Informatics student at the University of Jember who is interested in the multimedia field, especially in the fields of design, photo editing and video editing. I am hardworking, responsible and able to work in a team
            </p>
            <div class="grid md:grid-cols-2 gap-x-6">
              <a href="mailto:gavriel.ifl@gmail.com" target="_blank"  class="rounded-lg text-white text-center py-3 mb-5 md:mb-0 font-semibold" style="background-image: linear-gradient(to right, #D6009A , #B800D6)"> 
                <button type="button" >Contact me!</button>
              </a>
              <a href="https://www.canva.com/design/DAEjtR8gUmk/E7BKw02RlN3U836VkT7zwQ/view?utm_content=DAEjtR8gUmk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">
                <button type="button" class="w-full h-full text-white py-3 grounded-radiants font-semibold">Download CV</button>
              </a>
            </div>
          </div>
        </div>

        <div class="transform transition duration-200 hover:scale-105">
          <img
            src="/gavriel.png"
            class="w-full shadow-lg fancy-border-radius rotate-lg-6"
            alt=""
          />
        </div>
      </div>
      <div class="animate-bounce">
        <img src="/shape.svg" alt="" class="m-auto h-7">
      </div>
    </div>
    <!-- Jumbotron -->
  </section>
  <!-- Section: Design Block -->

</div>
</template>

<style>
  .grounded-radiants {
    position: relative;
    padding-top: 5px;
    padding-bottom: 5px;
    display: inline-block;
      /* border-image: linear-gradient(to right, #D6009A , #B800D6) 5; */
  }

  @media screen and (max-width: 766px) {
    .grounded-radiants {
      padding-top: 13px;
      padding-bottom: 13px;
    }
  }

  .grounded-radiants::before {
    content: "";
    position: absolute;
    inset: 0;
    border-radius: 10px;
    padding: 3px; /* control the border thickness */
    background: linear-gradient(to right, #D6009A , #B800D6);
    -webkit-mask: 
      linear-gradient(#fff 0 0) content-box, 
      linear-gradient(#fff 0 0);
    -webkit-mask-composite: xor;
            mask-composite: exclude;
    pointer-events: none;
      /* border-image: linear-gradient(to right, #D6009A , #B800D6) 5; */
  }


</style>