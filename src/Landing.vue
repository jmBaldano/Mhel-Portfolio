<script setup>
import Layout from "./layouts/Layout.vue";
</script>

<template>
  <title>Homepage</title>
  <Layout />
  <div class="grid grid-cols-12 items-center  pt-25 pl-10">
  <!-- <div class="flex items-center justify-between pt-25 pl-10"> -->
    <!-- Desc-->
    <div class="md:w-2/3 w-full md:pl-30 col-span-8 ">
      <h1 class="md:text-7xl text-5xl font-bold mb-4 text-[#B87C4C] w-full">
        HI!
        I'M
        <span
          class="font-serif text-amber-900 typing-text border-text-amber-900 overflow-hidden border-r-2 whitespace-nowrap block ">
          Melanie <br class="md:hidden block"><span class=" " >Baldano</span> </span> 
      </h1>
      <!-- <h1 class="md:text-7xl text-5xl font-bold mb-4 text-[#B87C4C]">
        HI! <br />
        I'M
        <span
          class="font-serif text-amber-900 whitespace-nowrap">
          Melanie </span> <span class="font-serif text-amber-900 typing-text border-text-amber-900 overflow-hidden border-r-2 whitespace-nowrap md:block">Baldano</span>
      </h1> -->
      <p class="text-[#B87C4C] leading-relaxed font-sans whitespace-pre-wrap w-full text-2xl md:text-3xl">
        Your <strong>Admin</strong> &amp; <strong>HR Specialist</strong>
      </p>
    </div>

    <!--Image -->
    <div class="col-span-4  flex justify-end">
    <div class=" md:w-full w-full relative border-b-2 border-amber-300 ">
      <img
        src="./images/atedp.png"
        alt="Face pic"
        class="md:w-full w-full h-[600px] object-cover transform z-10 overflow-visible"/>
      <!-- <div class="absolute inset-0 flex items-center justify-center pt-100 pr-50">
        <p class="fixed pr-100 text-[#DC143C] text-2xl font-thin">
          MELANIE BALDANO <span class="font-bold text-3xl">:</span>
        </p>
      </div> -->
      <div class="absolute inset-0 flex items-center justify-center pt-100 pr-50">
        <img
          src="./images/wholebody.png"
          alt="Whole body pic"
          class="absolute w-auto h-[200px] transition-transform duration-500 ease-in-out hover:scale-200 hover:-rotate-6"/>
      </div>
    </div>
    </div>
  </div>
</template>
<style>
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 12.5ch;
  } /* adjust to match text length */
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

.typing-text {
  animation: typing 3s steps(24) 1s 1 normal both, blink 0.7s step-end infinite alternate;
}
</style>
