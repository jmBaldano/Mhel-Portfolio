<script setup>
import Landing from './Landing.vue';
import About from './About.vue';
import Gallery from './Gallery.vue';
</script>

<template>
    <main>
        <section id="Landing" class="min-h-screen bg-[#EDE8D0]"> <Landing /></section>
        <section id="About" class="min-h-screen bg-[#EDE8D0]"> <About /></section>
        <!-- <section id="About" class="min-h-screen bg-[#FFE6D4]"> <About /></section> -->
        <section id="Gallery" class="min-h-screen bg-[#FFE6D4]"> <Gallery /></section>
    </main>
</template>