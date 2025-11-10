<script setup>
import { ref } from "vue";
const isMenuOpen = ref(false);

const toggleMenu = () => {
  isMenuOpen.value = !isMenuOpen.value;
};

const closeMenu = () => {
  isMenuOpen.value = false;
};
</script>
<template>
  <div class="relative">
    <header class="absolute z-50 w-full px-10">
      <nav class="flex items-center justify-between text-center">
        <div class="">
          <a href="#Landing"
            ><img
              src="../images/logo.png"
              alt="logo"
              class="block mx-auto max-w-[100px] md:max-w-[150px] h-auto"
          /></a>
        </div>
        <div
          class="uppercase space-x-20 pb-0 text-amber-600 font-thin px-20 hidden md:block"
        >
          <a href="#Landing" class="line">HOME</a>
          <a href="#About" class="line">ABOUT</a>
          <a href="" class="line">CONTACT</a>
          <a href="./CV Baldano Melanie Busa.pdf" target="_blank" class="line">CV</a>
        </div>
         <button @click="toggleMenu" class="p-2 transition-colors rounded-full md:hidden hover:bg-white/10">
            <div class="flex flex-col items-center justify-center cursor-pointer w-6 h-6 pl-40 md:pl-0">
                <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-300" :class="{ 'rotate-45  translate-y-1.5': isMenuOpen }"></span>
                <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-100" :class="{ 'opacity-0': isMenuOpen }"></span>
                <span class="block w-5 h-0.5 bg-black mt-1 transition-all duration-500" :class="{ '-rotate-45 -translate-y-1.5': isMenuOpen }"></span>
            </div>
        </button>
      </nav>
      <div v-if="isMenuOpen" class="inset-0 z-50 fixe md:hidden" @click.self="closeMenu">

  <div class="fixed w-64 font-bold bg-white shadow-xl top-20 right-4 backdrop-blur-md rounded-2xl mt-5">
    <nav class="p-6 space-y-0">
      <a href="#Landing" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">HOME</a>
      <a href="#About" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">ABOUT</a>
      <a href="#Contact" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">CONTACT</a>
      <a href="./CV Baldano Melanie Busa.pdf" @click="closeMenu" class="block px-4 py-3 font-light text-gray-900 rounded-lg line ">CV</a>
    </nav>
  </div>
  </div>
  <div class="border-b border-amber-700 w-[1200px] mx-auto"></div>
    </header>
  </div>

  <div class="fixed p-2 space-y-4  -translate-y-3.5 bottom-70 left-0 md:left-5 ~sm/md:~mr-12/60">
    <!-- Email -->
    <a href="mailto:yourname@example.com" 
    target="_blank" 
    class="p-2 transition duration-300 rounded-full">
    <svg xmlns="http://www.w3.org/2000/svg" 
        class="socicons w-7 h-7 text-amber-600" 
        fill="currentColor" viewBox="0 0 24 24">
      <path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/>
    </svg>
  </a>

    <a href="https://www.linkedin.com/in/john-mark-baldano-b2b69033b/" target="_blank" 
       class="p-2 transition duration-300 rounded-full  ">
        <svg xmlns="http://www.w3.org/2000/svg" 
             class="socicons w-7 h-7 text-amber-600" fill="currentColor" viewBox="0 0 24 24">
            <path d="M20.447 20.452h-3.554V14.81c0-1.345-.027-3.078-1.877-3.078-1.88 0-2.169 1.463-2.169 2.973v5.747H9.293V9h3.415v1.561h.048c.476-.9 1.637-1.847 3.372-1.847 3.604 0 4.27 2.372 4.27 5.456v6.282zM5.337 7.433a2.062 2.062 0 1 1 0-4.125 2.062 2.062 0 0 1 0 4.125zM6.886 20.452H3.788V9h3.098v11.452z"/>
        </svg>
    </a>
    <!-- IG -->
    <a href="https://www.instagram.com/yourusername"
   target="_blank"
   class="p-2 transition duration-300 rounded-full">
  <svg xmlns="http://www.w3.org/2000/svg"
       class="socicons w-7 h-7 text-amber-600"
       fill="currentColor" viewBox="0 0 24 24">
    <path d="M7.75 2h8.5A5.75 5.75 0 0 1 22 7.75v8.5A5.75 5.75 0 0 1 16.25 22h-8.5A5.75 5.75 0 0 1 2 16.25v-8.5A5.75 5.75 0 0 1 7.75 2zm0 1.5A4.25 4.25 0 0 0 3.5 7.75v8.5A4.25 4.25 0 0 0 7.75 20.5h8.5a4.25 4.25 0 0 0 4.25-4.25v-8.5A4.25 4.25 0 0 0 16.25 3.5h-8.5zM12 7a5 5 0 1 1 0 10 5 5 0 0 1 0-10zm0 1.5a3.5 3.5 0 1 0 0 7 3.5 3.5 0 0 0 0-7zm5.25-.88a.88.88 0 1 1 0 1.76.88.88 0 0 1 0-1.76z"/>
  </svg>
</a>


    <!-- facebook  -->
    <a href="https://www.facebook.com/yourusername" 
    target="_blank" 
    class="p-2 transition duration-300 rounded-full">
    <svg xmlns="http://www.w3.org/2000/svg" 
        class="socicons w-7 h-7 text-amber-600" 
        fill="currentColor" viewBox="0 0 24 24">
      <path d="M22.675 0h-21.35C.597 0 0 .598 0 1.333v21.333C0 23.402.597 24 1.325 24h11.495v-9.294H9.691v-3.622h3.129V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.764v2.312h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.402 24 22.667V1.333C24 .598 23.403 0 22.675 0z"/>
    </svg>
  </a>

</div>
</template>
