<template>
  <footer :class="`w-full text-white py-4 px-4 md:px-20 mt-auto bg-primary ${bgColor}`">
    <div class="container mx-auto flex flex-wrap justify-between items-center space-y-4 md:space-y-0">
      <div class="w-full md:w-auto text-center md:text-left text-sm">FOOTER BRANDING</div>
      <div class="w-full md:w-auto text-center md:text-left"><nuxt-link to="#">About</nuxt-link></div>
      <div class="w-full md:w-auto text-center md:text-left"><nuxt-link to="#">Privacy</nuxt-link></div>
      <div class="w-full md:w-auto text-center md:text-left flex space-x-2.5">
  <i-mdi-github style="color: white" class="text-xl md:text-2xl" />
  <i-mdi-instagram style="color: white" class="text-xl md:text-2xl" />
  <i-mdi-linkedin style="color: white" class="text-xl md:text-2xl" />
</div>

    </div>
  </footer>
</template>

<script>
export default {
  props: {
    bgColor: {
      type: String,
      default: 'bg-green',
    },
  },
};
</script>

<style scoped></style>
