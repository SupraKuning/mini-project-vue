<template>
  <div class="background-all">
    <Navbar2 />
    <Preloader v-if="showHideSpinner" />
    <Nuxt class="pt-16" />
    <Footer />
  </div>
</template>

<script>
export default {
  data () {
    return {
      showHideSpinner: true
    }
  },
  beforeCreate () {
    this.showHideSpinner = true
  },
  mounted () {
    this.showHideSpinner = false
  }
}
</script>

<style>
.background-all{
  background-image: url('/images/background.svg');
  background-size: 100%;
}

.backdrop-filter-custom{
  background-color: rgba(0,30,38,.6);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  -moz-backdrop-filter: blur(12px);
}

::-webkit-scrollbar {
    width: 8px;
}

::-webkit-scrollbar-track {
    width: 12px;
}

::-webkit-scrollbar-thumb {
    background-color: #b5b5bd;
}

::-webkit-scrollbar-thumb:hover {
    background: #10b981;
}

a.nuxt-link-exact-active {
  color: #10b981 !important;
  border-bottom-width: 4px;
  border-color: rgb(16, 185, 129);
}
</style>
