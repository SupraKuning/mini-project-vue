<template>
  <div>
    <NuxtLink to="/portfolioPage">
      <h2 class="pt-10 text-4xl text-white font-bold mb-8 display-5 text-center">
        Some of my works
      </h2>
    </NuxtLink>
    <div class="container m-auto">
      <div class="text-center md:px-36 md:text-right">
        <NuxtLink to="/portfolioPage">
          <button>
            <div
              class="relative block shadow-2xl shadow-lg mx-3 mb-4 px-8 py-3 rounded-full text-white transform transition duration-200 hover:scale-105"
              style="background: hsla(0, 0%, 20%, 0.55); backdrop-filter: blur(30px); z-index: 1"
            >
              More &nbsp;&nbsp;
              <img src="/right.svg" class="inline" />
            </div>
          </button>
        </NuxtLink>
      </div>
      <div class="container mx-auto xl:px-32 text-center lg:text-left grid lg:grid-cols-3" >
        <div class="relative block rounded-lg shadow-2xl m-5 transform transition duration-200 hover:scale-105" >
          <NuxtLink to="/detail">
            <img class="rounded-t-lg p-5 m-auto" src="/Group 49.svg" alt="" />
            <div class="p-5">
                <h5 class="mb-2 mx-2 text-2xl font-bold tracking-tight text-white text-center" >
                  Debate Day | HMIF Election Vote 2021
                </h5>
              <p class="mb-3 mx-5 font-extralight text-white">
                Debat Calon Ketua Umum dan Calon Wakil Ketua Umum Himpunan Mahasiswa Informatika Universitas Jember Periode 2021-2022 HMIF Election Vote 2021 berbentuk live streaming melalui platform zoom.
              </p>
            </div>
          </NuxtLink>
        </div>

        <div class="relative block rounded-lg shadow-2xl m-5 transform transition duration-200 hover:scale-105" >
          <NuxtLink to="/detail2">
            <img class="rounded-t-lg p-5 m-auto" src="/Group 50.svg" alt="" />
            <div class="p-5">
                <h5
                  class="mb-2 mx-2 text-2xl font-bold tracking-tight text-white text-center"
                >
                  Masuk himpunan ngapain aja sih? - Ngobrol Santuy S3 E1
                </h5>
              <p class="mb-3 mx-5 font-extralight text-white">
                Selamat datang di Ngobrol Santuy season 3, spesial di episode spesial Hari Ulang Tahun HMIF ke-3 Di episode ini host kita, Aghnia Faza ngobrol ngobrol santuy dengan 2 BPH kita yang yang cantik cantik.
              </p>
            </div>
          </NuxtLink>
        </div>

        <div
          class="relative block rounded-lg shadow-2xl m-5 transform transition duration-200 hover:scale-105"
        >
          <a href="#">
            <img class="rounded-t-lg p-5 m-auto" src="/Group 51.svg" alt="" />
          </a>
          <div class="p-5">
            <a href="#">
              <h5
                class="mb-2 mx-2 text-2xl font-bold tracking-tight text-white text-center"
              >
                Video Akreditasi Program Studi Informatika Universitas Jember
              </h5>
            </a>
            <p class="mb-3 mx-5 font-extralight text-white">
              Pembuatan Video untuk keperluan proses akreditasi salah satu prodi di Fakultas Ilmu Komputer Universitas Jember
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
