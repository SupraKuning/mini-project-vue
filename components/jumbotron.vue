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
            class="relative block rounded-lg shadow-lg px-6 py-12 md:px-12 lg:-mr-14"
            style="background: hsla(0, 0%, 100%, 0.55); backdrop-filter: blur(30px); z-index: 1"
          >
            <h2 class="text-3xl text-white font-bold mb-4 display-5">Hello, i'm Gavriel</h2>
            <p class="text-white">
                Graphic Designer, UI/UX Designer & Video Editor
            </p>
            <p class="mb-12 text-white">
              Nunc tincidunt vulputate elit. Mauris varius purus malesuada neque iaculis
              malesuada. Aenean gravida magna orci, non efficitur est porta id. Donec magna
              diam.
            </p>

            <div class="grid md:grid-cols-2 gap-x-6">
              <button type="button" class="rounded-lg text-white py-2" style="background-image: linear-gradient(to right, #D6009A , #B800D6)">Contact me!</button>
              <button type="button" class="rounded-lg text-black py-2" style="border-radius: 50%; border-width: 3px; border-image: radial-gradient(#D6009A, #B800D6, #D6009A, #B800D6, #D6009A) 1;">Download CV</button>
            </div>
          </div>
        </div>

        <div>
          <img
            src="/gavriel.png"
            class="w-full shadow-lg fancy-border-radius rotate-lg-6"
            alt=""
          />
        </div>
      </div>
    </div>
    <!-- Jumbotron -->
  </section>
  <!-- Section: Design Block -->

</div>
</template>