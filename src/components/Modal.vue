<template>
  <dialog :id="modal" class="w-11/12 2xl:w-1/2 lg:w-3/4 p-5 bg-white rounded-md" @click="close">
    <div class="flex flex-col w-full h-auto" @click.stop>
      <!-- Header -->
      <div class="flex w-full h-auto justify-center items-center">
        <div class="flex w-10/12 h-auto py-2 text-2xl font-bold">
          {{ modal }}
        </div>
        <div @click="close" class="flex w-1/12 h-auto justify-end cursor-pointer">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-x"><line x1="18" y1="6" x2="6" y2="18"></line><line x1="6" y1="6" x2="18" y2="18"></line></svg>
        </div>
        <!--Header End-->
      </div>
      <!-- Modal Content-->
      <div class="flex flex-col text-xl w-full h-auto mt-2 py-10 px-2 justify-center items-center bg-gray-200 rounded text-center text-gray-600">
        <div class="font-bold" v-if="getCookie('lang') == 'eng'">{{ desc }}</div>
        <div class="font-bold" v-if="getCookie('lang') == 'kr'">{{ descKR }}</div>
        <div class="flex flex-col lg:flex-row">
          <img
          v-bind:src="img"
          v-bind:alt="img"
          class="object-cover my-6 max-h-80 rounded lg:w-3/4 ml-4"
          /> 
          <div class="m-6 mt-0 lg:mt-12 lg:text-left lg:w-1/2">
            <span v-if="getCookie('lang') == 'eng'">{{ longdesc }}</span>
            <span v-if="getCookie('lang') == 'kr'">{{ longdescKR }}</span>
          </div>
        </div>
        <div class="flex justify-center align-middle">
          <div class="space-x-2 justify-center">
          <div v-for="tag in tags" :key="tag" class="bg-azure px-3 py-1 font-semibold text-sm inline-flex rounded-full">
            {{ tag }}
          </div>
        </div>
        <a :href="link" target="_blank" class="ml-5">
          <button class="bg-celadonBlue hover:bg-prussianBlue">
            <span>Open Link</span>
          </button>
        </a>
        </div>
      </div>

      <!-- <a :href="link" target="_blank" class="m-auto mt-6">
        <button class="bg-celadonBlue hover:bg-prussianBlue">
          <span>Open Link</span>
        </button>
      </a> -->
      <!-- End of Modal Content-->
    </div>
  </dialog>
</template>

<script>
import {getCookie} from '../cookie';

export default {
  name: 'Modal',
  props: {
    modal: String,
    year: String,
    link: String,
    desc: String,
    descKR: String,    
    longdesc: String,
    longdescKR: String,
    img: String,
    tags: Array,
  },
  methods: {
    getCookie,
    outClose(){
      let isClickInsideElement = document.getElementById(this.modal).contains(event.target);
      console.log(isClickInsideElement);
      if (!isClickInsideElement) {
        this.close();
      }
    },
    close() {
      document.getElementById(this.modal).close();
    }
  }
}
</script>

<style scoped>
dialog[open] {
  animation: appear .15s cubic-bezier(0, 1.8, 1, 1.8);
}

dialog::backdrop {
  background: linear-gradient(45deg, rgba(0, 0, 0, 0.5), rgba(54, 54, 54, 0.5));
  backdrop-filter: blur(3px);
}


@keyframes appear {
  from {
    opacity: 0;
    transform: translateX(-3rem);
  }

  to {
    opacity: 1;
    transform: translateX(0);
  }
}
</style>

