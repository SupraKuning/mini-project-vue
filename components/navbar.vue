<template>
  <div class="bg-transparent w-full h-full">
    <nav class="w-full mx-auto bg-transparent shadow">
      <div
        class="container px-6 py-10 justify-between h-16 flex items-center lg:items-stretch mx-auto"
      >
        <div class="h-full w-full flex items-center">
          <div class="mr-10 flex items-center">
            <img src="/logo gav.png" class="mr-3 h-6 sm:h-9" alt="Logo gav" />
          </div>

          <ul class="pr-12 xl:flex items-center h-full m-auto text-center hidden custom">
            <li
              class="hover:text-gray-400 cursor-pointer h-full flex items-center text-sm text-white tracking-normal"
            >
              <NuxtLink to="/">
                Home
              </NuxtLink>
            </li>
            <li
              class="hover:text-white cursor-pointer h-full flex items-center text-sm text-gray-400 mx-10 tracking-normal"
            >
              <NuxtLink to="/portfolioPage">
               Portfolio
              </NuxtLink>
            </li>
          </ul>
        </div>

        <div class="h-full xl:flex items-center justify-end hidden">
          <div class="w-full h-full flex items-center">
            <div class="w-full h-full flex">
              <div class="flex items-center md:order-2">
                <a href="https://instagram.com/gavrielijlal" target="_blank">
                  <button
                    type="button"
                    class="flex mr-3 text-sm md:mr-0"
                    id="user-menu-button"
                    aria-expanded="false"
                    data-dropdown-toggle="dropdown"
                  >
                    <span class="sr-only">Open user menu</span>
                    <img class="m-3" src="/instagram.png" alt="instagram" />
                  </button>
                </a>
                <a
                  href="https://www.linkedin.com/in/gavrelijlal/"
                  target="_blank"
                >
                  <button
                    type="button"
                    class="flex mr-3 text-sm md:mr-0"
                    id="user-menu-button"
                    aria-expanded="false"
                    data-dropdown-toggle="dropdown"
                  >
                    <span class="sr-only">Open user menu</span>
                    <img class="m-3" src="/linkedin.png" alt="linkedin" />
                  </button>
                </a>
                <a href="https://github.com/SupraKuning" target="_blank">
                  <button
                    type="button"
                    class="flex mr-3 text-sm md:mr-0"
                    id="user-menu-button"
                    aria-expanded="false"
                    data-dropdown-toggle="dropdown"
                  >
                    <span class="sr-only">Open user menu</span>
                    <img class="m-3" src="/githab.png" alt="githab" />
                  </button>
                </a>
                <a href="mailto:gavriel.ifl@gmail.com" target="_blank">
                  <button
                    type="button"
                    class="flex mr-3 text-sm md:mr-0"
                    id="user-menu-button"
                    aria-expanded="false"
                    data-dropdown-toggle="dropdown"
                  >
                    <span class="sr-only">Open user menu</span>
                    <img class="m-3" src="/vector.png" alt="email" />
                  </button>
                </a>
                <div
                  class="hidden z-50 my-4 text-base list-none bg-white rounded divide-y divide-gray-100 shadow"
                  id="dropdown"
                  data-popper-reference-hidden=""
                  data-popper-escaped=""
                  data-popper-placement="top"
                  style="
                    position: absolute;
                    inset: auto auto 0px 0px;
                    margin: 0px;
                    transform: translate(1246px, 801px);
                  "
                >
                  <div class="py-3 px-4">
                    <span class="block text-sm text-gray-900 dark:text-white"
                      >Bonnie Green</span
                    >
                    <span
                      class="block text-sm font-medium text-gray-500 truncate dark:text-gray-400"
                      >name@flowbite.com</span
                    >
                  </div>
                  <ul class="py-1 list-none" aria-labelledby="dropdown">
                    <li>
                      <a
                        href="#"
                        class="block py-2 px-4 text-sm text-gray-700 hover:bg-gray-100"
                        >Dashboard</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block py-2 px-4 text-sm text-gray-700 hover:bg-gray-100"
                        >Settings</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block py-2 px-4 text-sm text-gray-700 hover:bg-gray-100"
                        >Earnings</a
                      >
                    </li>
                    <li>
                      <a
                        href="#"
                        class="block py-2 px-4 text-sm text-gray-700 hover:bg-gray-100"
                        >Sign out</a
                      >
                    </li>
                  </ul>
                </div>
                <button
                  data-collapse-toggle="mobile-menu-2"
                  type="button"
                  class="inline-flex items-center p-2 ml-1 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200"
                  aria-controls="mobile-menu-2"
                  aria-expanded="false"
                >
                  <span class="sr-only">Open main menu</span>
                  <svg
                    class="w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <svg
                    class="hidden w-6 h-6"
                    fill="currentColor"
                    viewBox="0 0 20 20"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </div>

        <div class="visible xl:hidden flex items-center">
          <ul
            class="z-40 p-2 border-r absolute rounded top-0 left-0 right-0 shadow mt-16 md:mt-16 hidden list-none" style="background: hsla(0, 0%, 40%, 0.55); backdrop-filter: blur(30px); z-index: 2"
          >
            <li
              class="flex xl:hidden cursor-pointer text-white text-base leading-3 tracking-normal mt-2 py-3 hover:text-grey-400 focus:text-grey-400 focus:outline-none"
            >
              <NuxtLink to="/">
                <span class="leading-6 ml-2 font-bold">Home </span>
              </NuxtLink>
            </li>
            <li
              class="xl:hidden cursor-pointer text-gray-400 text-base leading-3 tracking-normal py-3 hover:text-white flex items-center focus:text-indigo-700 focus:outline-none"
            >
              <NuxtLink to="/portfolioPage">
                <span class="leading-6 ml-2 font-bold">Portfolio</span>
              </NuxtLink>
            </li>
          </ul>

          <svg
            @click="MenuHandler($event, true)"
            aria-haspopup="true"
            aria-label="Main Menu"
            v-bind:xmlns="xmlns"
            class="show-m-menu icon icon-tabler icon-tabler-menu"
            width="28"
            height="28"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="#fff"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z"></path>
            <line x1="4" y1="8" x2="20" y2="8"></line>
            <line x1="4" y1="16" x2="20" y2="16"></line>
          </svg>
          <div class="hidden close-m-menu" @click="MenuHandler($event, false)">
            <svg
              aria-label="Close"
              v-bind:xmlns="xmlns"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="#fff"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" />
              <line x1="18" y1="6" x2="6" y2="18" />
              <line x1="6" y1="6" x2="18" y2="18" />
            </svg>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "LightWithGreyBackground",
  data() {
    return {
      xmlns: "http://www.w3.org/2000/svg",
      xlink: "http://www.w3.org/1999/xlink",
      profilePhoto:
        "https://tuk-cdn.s3.amazonaws.com/assets/components/boxed_layout/bl_1.png",
    };
  },
  methods: {
    dropdownHandler(event) {
      let single = event.currentTarget.getElementsByTagName("ul")[0];
      single.classList.toggle("hidden");
    },
    MenuHandler(el, val) {
      let MainList =
        el.currentTarget.parentElement.getElementsByTagName("ul")[0];
      let closeIcon =
        el.currentTarget.parentElement.getElementsByClassName(
          "close-m-menu"
        )[0];
      let showIcon =
        el.currentTarget.parentElement.getElementsByClassName("show-m-menu")[0];
      if (val) {
        MainList.classList.remove("hidden");
        el.currentTarget.classList.add("hidden");
        closeIcon.classList.remove("hidden");
      } else {
        showIcon.classList.remove("hidden");
        MainList.classList.add("hidden");
        el.currentTarget.classList.add("hidden");
      }
    },
  },
};
</script>

<style scoped>
ul li::before {
    content: "";
    color: white;
}
</style>