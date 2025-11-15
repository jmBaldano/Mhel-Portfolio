<script setup>
import Landing from './Landing.vue';
import About from './About.vue';
import Gallery from './components/Gallery.vue';
import Contact from './Contact.vue';
import Footer from './layouts/Footer.vue';
</script>

<template>
    
    <main class="bg-[#EDE8D0]">
        <Layout>
        <section id="Landing" class="min-h-screen bg-[#EDE8D0]"> <Landing /></section>
        <section id="About" class="min-h-screen bg-[#EDE8D0]"> <About /></section>
        <section id="Contact" class="min-h-screen bg-[#EDE8D0]"> <Contact /></section>
        <!-- <section id="About" class="min-h-screen bg-[#FFE6D4]"> <About /></section> -->
        </Layout>
    </main>
    
</template>