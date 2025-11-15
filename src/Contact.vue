<script setup>
import Footer from './layouts/Footer.vue';
</script>
<template>
    <div class="">
        <div class="border-b border-amber-700 w-[1200px] mx-auto pt-10"></div>
        <div data-aos="fade-up" class="py-20 space-y-5">
            <h1 class="uppercase text-4xl font-serif text-center">Get in touch</h1>
             <p class=" font-thin uppercase text-center ">Looking for someone with my skills and experience? feel free to reach out!</p>
        </div>
        <div class="grid grid-cols-12 text-center  h-full mx-20 space-x-20">

            <section data-aos="fade-right" class="col-span-12 lg:col-span-6 order-2 lg:order-1 text-left space-y-15 pl-12">
                <div class="lg:text-left text-center">
                <h2 class="text-5xl ">Call or Message me!</h2> 
                    <div class="flex items-center gap-2 text-gray-700">
                    <!-- <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 text-gray-900" fill="none" 
                        viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" 
                        d="M3 5a2 2 0 012-2h3l2 5-2 1a11 11 0 005 5l1-2 5 2v3a2 2 0 01-2 2h-1C8.82 19 5 15.18 5 10V9a2 2 0 00-2-2z" />
                    </svg> -->
                        <span class="font-thin text-3xl pl-10 lg:pl-0">+63 906 218 1722</span>
                    </div>
                </div>

            <section class="space-y-0 ">
            <p class="font-thin text-center text-2xl">Connect with my socials</p>
                <div class="flex justify-center text-7xl font-thin ">
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">FACEBOOK</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">LINKEDIN</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">INSTAGRAM</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">FACEBOOK</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">LINKEDIN</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">FACEBOOK</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">LINKEDIN</a>
                    <a href="" class="[writing-mode:vertical-rl] hover:scale-90 hover:text-gray-500 duration-300">INSTAGRAM</a>
                </div>
            </section>

            </section>
            <section data-aos="fade-left" class="col-span-12 lg:col-span-6 order-1 lg:order-2 pl-25 border-l">
                <!-- <h2 class="text-4xl font-thin">Looking for someone with my skills and experience? feel free to reach out.</h2>
                <h1 class="">LET’S CONNECT!</h1> -->
                <form class="flex flex-col space-y-4">
                    <label for="name" class="flex justify-start font-thin uppercase">Name:</label>
                    <input name="Name" id="name" type="text" class="border-b focus:outline-none w-1/2 focus:border-b-2" required>
                    <label for="email" class="flex justify-start font-thin uppercase">Email:</label>
                    <input name="Email" id="email" type="email" class="border-b focus:outline-none w-1/2 focus:border-b-2" required>
                    <label for="subject" class="flex justify-start font-thin uppercase">Subject:</label>
                    <input name="Subject" id="subject" type="text" class="border-b focus:outline-none w-1/2 focus:border-b-2" required>
                    <label for="message" class="flex justify-start font-thin uppercase">Message:</label>
                    <textarea name="message" id="email" class="w-full h-30 border focus:outline focus:border-b-2" required></textarea>
                    <button type="submit" class="border h-12 font-thin uppercase cursor-pointer hover:bg-gray-100 duration-300" >
                    Send Message
                    </button>  
                </form>
            </section>
        </div>
        <div class="col-pan-12 pl-5 pb-10 w-30 mb-5 ml-5 duration-300 hover:-translate-y-3">
        <a data-aos="fade-up" href="#Landing" class="block">
            <svg width="100" height="100" viewBox="0 0 24 24">
            <path d="M12 6l-6 6h12z" stroke="black" fill="black" class=" translate-y-3 "/>
            </svg>
        </a>
        </div>
    <Footer />
    </div>
</template>