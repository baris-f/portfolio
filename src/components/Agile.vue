<template>
  <div class="bg-blue-500 rounded-l rounded-md w-11/12 sm:w-3/4 flex font-sans h-80">
    <div class="flex flex-wrap space-x-4 my-5">
      <div class="hidden 2xl:block rounded w-64 p-2 zoom" style="background-color: #dae4e9;">
        <div class="flex justify-between py-1">
          <h3 class="text-sm pl-10 font-bold">Backlog</h3>
          <svg class="h-4 fill-current text-grey-dark cursor-default" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5 10a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4z"/></svg>
        </div>
        <!-- TODO:Use type.js -->
        <div class="text-sm mt-2">
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Manage and launch big video game project
          </div>
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Master Korean language
          </div>
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Improve continuous integration
          </div>
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Drive user testing
          </div>
          <p class="mt-3 text-grey-dark">Add a card...</p>
        </div>
      </div>
      <div class="hidden xl:block rounded w-64 p-2 zoom" style="background-color: #dae4e9;">
        <div class="flex justify-between py-1">
          <h3 class="text-sm pl-6 font-bold">Doing</h3>
          <svg class="h-4 fill-current text-grey-dark cursor-default" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5 10a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4z"/></svg>
        </div>
        <div class="text-sm mt-2">

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Improve portfolio
            <div class="text-grey-darker mt-2 ml-2 flex justify-between items-start">
              <span class="text-xs flex items-center">
              <svg class="h-4 fill-current mr-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50"><path d="M11 4c-3.855 0-7 3.145-7 7v28c0 3.855 3.145 7 7 7h28c3.855 0 7-3.145 7-7V11c0-3.855-3.145-7-7-7zm0 2h28c2.773 0 5 2.227 5 5v28c0 2.773-2.227 5-5 5H11c-2.773 0-5-2.227-5-5V11c0-2.773 2.227-5 5-5zm25.234 9.832l-13.32 15.723-8.133-7.586-1.363 1.465 9.664 9.015 14.684-17.324z"/></svg>
                2/3
              </span>
              <img src="favicon.ico" class="h-8" />
            </div>
          </div>

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Reading "The Scrum Guide"
          </div>
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Looking for a job in South Korea
          </div>
          <p class="mt-3 text-grey-dark">Add a card...</p>
        </div>
      </div>
      <div class="hidden md:block rounded w-64 p-2 zoom" style="background-color: #dae4e9;">
        <div class="flex justify-between py-1">
          <h3 class="text-sm pl-4 font-bold">Testing</h3>
          <svg class="h-4 fill-current text-grey-dark cursor-default" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5 10a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4z"/></svg>
        </div>
        <div class="text-sm mt-2">
          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Applied to V.I.E.
          </div>

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Speak and practice Korean
          </div>

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Use Transformation Digital knowledge in projects
            <div class="text-grey-darker mt-2 ml-2 flex justify-between items-start">
              <span class="text-xs flex items-center">
              <svg class="h-4 fill-current mr-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50"><path d="M11 4c-3.855 0-7 3.145-7 7v28c0 3.855 3.145 7 7 7h28c3.855 0 7-3.145 7-7V11c0-3.855-3.145-7-7-7zm0 2h28c2.773 0 5 2.227 5 5v28c0 2.773-2.227 5-5 5H11c-2.773 0-5-2.227-5-5V11c0-2.773 2.227-5 5-5zm25.234 9.832l-13.32 15.723-8.133-7.586-1.363 1.465 9.664 9.015 14.684-17.324z"/></svg>
                3/5
              </span>
              <img src="favicon.ico" class="h-8" />
            </div>
          </div>
          <p class="mt-3 text-grey-dark">Add a card...</p>
        </div>
      </div>
      <div class="rounded w-64 p-2 zoom" style="background-color: #dae4e9;">
        <div class="flex justify-between py-1">
          <h3 class="text-sm pl-3 font-bold">Done</h3>
          <svg class="h-4 fill-current text-grey-dark cursor-default" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M5 10a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4zm7 0a1.999 1.999 0 1 0 0 4 1.999 1.999 0 1 0 0-4z"/></svg>
        </div>
        <div class="text-sm mt-2">

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter flex flex-row justify-between zoom">
            <div>Over 10 personal projects and games </div>
            <img src="favicon.ico" class="grow h-8 mt-6"/>
          </div>

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            Experience in Agile and Project Management
          </div>

          <div class="bg-white p-2 rounded mt-1 border-b border-grey cursor-default hover:bg-grey-lighter zoom">
            <p class="type"> IT Master Degree, confirmed developer</p>
          </div>
          <p class="mt-3 text-grey-dark">Add a card...</p>
        </div>
      </div>
    </div>
    <div class="absolute bg-gradient-to-r from-blue-500 via-transparent to-transparent rounded-l rounded-md w-3/4 h-80 t-0 l-0 z-0 pointer-events-none">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Agile'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
