<script setup>
import Layout from "./layouts/Layout.vue";
</script>

<template>
  <title>Homepage</title>
  <Layout />
  <div class="flex items-center justify-between pt-25 pl-10">
    <!-- Desc-->
    <div class="md:w-2/3 w-1/2 pl-0 md:pl-30">
      <h1 class="text-6xl font-bold mb-4 text-amber-300">
        HI! <br />
        I'M
        <span
          class="font-serif text-amber-900 typing-text border-text-amber-900 overflow-hidden border-r-2 whitespace-nowrap"
          >MHEL</span
        >
      </h1>
      <p class="text-[#CD2C58] leading-relaxed font-bold whitespace-pre-wrap w-full">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio, ea earum
        quisquam molestiae harum architecto ut maxime sint quod error recusandae quo
        similique in repellat, deserunt minima facilis magnam mollitia!
      </p>
    </div>

    <!--Image -->
    <div class="md:w-1/3 w-full relative border-b-2 border-amber-300">
      <img
        src="./images/atedp.png"
        alt="Face pic"
        class="md:w-full w-full h-[600px] object-cover transform z-10 transition-transform duration-500 ease-in-out hover:scale-110 hover:-rotate-2"
      />
      <!-- <div class="absolute inset-0 flex items-center justify-center pt-100 pr-50">
        <p class="fixed pr-100 text-[#DC143C] text-2xl font-thin">
          MELANIE BALDANO <span class="font-bold text-3xl">:</span>
        </p>
      </div> -->
      <div class="absolute inset-0 flex items-center justify-center pt-100 pr-50">
        <img
          src="./images/atedp2.png"
          alt="Whole body pic"
          class="absolute w-auto h-[200px] transition-transform duration-500 ease-in-out hover:scale-200 hover:-rotate-6"
        />
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
    width: 24ch;
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
