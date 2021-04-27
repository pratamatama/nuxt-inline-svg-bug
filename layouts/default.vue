<template>
  <div class="antialiased text-gray-800">
    <Navbar :is-menu-open="isMenuOpen" @toggle="isMenuOpen = !isMenuOpen" />
    <NavbarMenu v-show="isMenuOpen" />
    <div v-show="isMenuOpen" class="fixed inset-0 z-30 bg-white" />

    <Nuxt />

    <!-- <Footer /> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
    }
  },
}
</script>
