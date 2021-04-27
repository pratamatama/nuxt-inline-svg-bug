<template>
  <nav :class="navbarClass">
    <div class="flex items-center justify-between">
      <NuxtLink to="/" class="pl-8 uppercase font-bold text-3xl">
        COMPLOGO
      </NuxtLink>
      <button class="inline-block p-8" @click.prevent="$emit('toggle')">
        <IconMenu class="w-6 h-6" />
      </button>
    </div>
  </nav>
</template>

<script>
export default {
  props: {
    isMenuOpen: {
      type: Boolean,
      default: false,
    },
  },
  computed: {
    navbarClass() {
      return this.$route.name === 'index' && !this.isMenuOpen
        ? 'absolute top-0 inset-x-0 z-50 border-b border-gray-700 bg-gray-800 text-white'
        : 'sticky top-0 inset-x-0 z-50 border-b border-gray-200 bg-white'
    },
  },
}
</script>
