<template>
  <nav class="fixed w-full bg-cultured z-10">
    <!-- TODO:add shadow and separate on scroll-->
    <div class="container flex items-center justify-center p-5 mx-auto text-gray-800 capitalize dark:text-gray-300">

      <a href="#about" class="border-b-2 border-transparent hover:text-gray-900 dark:hover:text-gray-200 hover:border-celadonBlue mx-1.5 sm:mx-6">About</a>

      <a href="#agile" class="border-b-2 border-transparent hover:text-gray-900 dark:hover:text-gray-200 hover:border-celadonBlue mx-1.5 sm:mx-6">Agile</a>

      <a href="#projects" class="border-b-2 border-transparent hover:text-gray-900 dark:hover:text-gray-200 hover:border-celadonBlue mx-1.5 sm:mx-6">Projects</a>

    </div>
  </nav>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
