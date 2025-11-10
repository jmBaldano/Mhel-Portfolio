<script setup>
import Gallery from './components/Gallery.vue';
</script>
<template>
    <section class="grid grid-cols-12">
  <!-- LEFT SIDE -->
  <div class="col-span-12 md:col-span-8 ">
    <div>
      <h1 class="uppercase pl-37 md:text-7xl text-5xl font-bold tracking-widest text-amber-600">
        ABOUT ME
      </h1>
    </div>

    <div class="flex justify-start">
      <div class="w-2">
        <h1 class="uppercase p-20 pb-0 pt-0 md:text-7xl text-5xl font-bold [writing-mode:vertical-lr] tracking-widest text-amber-700">
          ABOUT ME
        </h1>
      </div>

      <div class="pl-40 pt-15  border-r-3 border-amber-300">
        <h2 class="text-2xl md:text-4xl uppercase font-thin text-amber-700 pb-5">
          A little info about me
        </h2>
        <p class="text-[#CD2C58] leading-relaxed font-sans whitespace-pre-wrap md:w-[800px] w-[300px] md:text-xl text-sm">
          Enthusiastic professional with a B.Sc. in Computer Science seeking an HR Coordinator position.
          Experienced in administration, quality control, and team leadership. Skilled in communication,
          multitasking, and fostering positive workplace relationships. Ready to contribute to organizational
          success in a dynamic HR environment.
        </p>
      </div>
    </div>
  </div>

  <!-- RIGHT SIDE -->
  <div class="col-span-12 md:col-span-4 flex justify-center items-center">
    <Gallery />
  </div>
</section>

        <div class="flex justify-between">
            <section class="w-full h-auto  border-r-2 border-amber-300 hidden md:block">
                <!-- <div class="overflow-hidden flex justify-end">
                    <img src="./images/atepic4.jpg" alt="Church Picture"
                    class="hover:scale-105 duration-300 w-[500px]">
                </div> -->
                <div>
                <Gallery />
                </div>
                <div class="flex justify-end  ">
                    <div class="p-10 w-full  md:w-[650px] hover:scale-95 duration-300 leading-tight pt-30">
                    <h2 class=" uppercase font-thin border-t-2 ml-5 text-5xl font-thing text-amber-800 tracking-widest p-10">
                        Academics
                    </h2>
                        <h1 class="text-3xl text-gray-900 flex justify-between">Bachelor of Science in Computer Science <i class="text-sm text-gray-500 pt-3">2016 - 2020</i></h1>
                        <i class="text-gray-500 text-xl">St. John Technological College of the Philippines</i>
                        <!-- <ul class="list-disc  marker:text-black text-justify">
                            <li><p class="leading-tight">Develop and integrated APIs to support frontend components, ensuring smooth communication between the frontend and backend</p></li>
                            <li>Identified API Errors & Fixing. Debugged API responses, fixed backend-related errors, and optimized API efficiency for better performance.</li>
                        </ul> -->
                        <h1 class="flex justify-between text-3xl text-gray-900 pt-5">Computer Secretarial<i class="text-sm text-gray-500 pt-3">2008 - 2010</i></h1>
                        <i class="text-gray-500 text-xl">Datamex Institute of Computer Technology, Quezon City</i>
                        <!-- <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Got deployed in a different project and created sidebar, revising UI to be responsive and implement it on their UI Web design</li>
                            <li>Output revision based on our clients and Team Lead desired</li>
                        </ul> -->
                    </div>
                </div>
            </section>
        <!--Acads & Experiences -->
            <section class=" ">
                <div class="flex justify-end whitespace-pre-wrap">
                      <h2 class="pt-80 uppercase text-5xl [writing-mode:vertical-rl] font-thin text-amber-700 tracking-widest ">
                        Experiences
                    </h2>
                    <div class="p-10 transform  border-t-2 border-amber-700 w-full md:w-[700px] hover:scale-95 transition-transform duration-300">
                        <h1 class="text-3xl text-gray-900 flex justify-between uppercase">Admin and HR Staff <i class="text-sm text-gray-500">June 2023 - Present</i></h1>
                        <i class="text-gray-500 text-xl">Paradigm Perspective</i>
                        <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Payroll management</li>
                            <li>Manpower management, including scheduling and workforce coordination</li>
                            <li>Filing documents</li>
                            <li>Handling expenses and liquidation processes</li>
                            <li>Canvassing and ordering construction materials</li>
                            <li>Managing deliveries and coordinating logistics</li>
                            <li>Processing government contribution remittances (SSS, PhilHealth, Pag-IBIG)</li>
                        </ul>
                        <h1 class="flex justify-between text-3xl text-gray-900 pt-5 uppercase">Admin and HR Staff<i class="text-sm text-gray-500">October 2020 - July 2023</i></h1>
                        <i class="text-gray-500 text-xl">LG Transtel Corporation</i>
                        <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Manpower management, including scheduling and workforce coordination</li>
                            <li>Billing and payroll processing</li>
                            <li>Daily reporting and filing documents</li>
                            <li>Scheduling appointments and meetings</li>
                            <li>Handling liquidation processes</li>
                            <li>Processing government contribution remittances (SSS, PhilHealth, Pag-IBIG)</li>
                        </ul>
                        <h1 class="flex justify-between text-3xl text-gray-900 pt-5 uppercase">Quality Control Staff,<i class="text-sm text-gray-500">June 2011 - January 2012</i></h1>
                        <i class="text-gray-500 text-xl">Nutritive Corporation</i>
                        <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Checked the quality of prepared products and recorded results during production</li>
                            <li>Inspected and packed final products ensuring adherence to quality standards</li>
                        </ul>
                        <h1 class="flex justify-between text-3xl text-gray-900 pt-5 uppercase">Quality Control Staff,<i class="text-sm text-gray-500">October 2010 - May 2011</i></h1>
                        <i class="text-gray-500 text-xl">Rebisco Republic Biscuit Corporation</i>
                        <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Monitored production processes to ensure product quality</li>
                            <li>Conducted inspections and packing of finished products</li>
                        </ul>
                    </div>
                    <h2 class=" uppercase text-5xl [writing-mode:vertical-rl] font-thin text-amber-300 tracking-widest  pr-5">
                        Experiences 
                    </h2>
                    
                </div>
                <!-- Academics -->
                <div class="flex justify-end md:hidden ">
                    <div class="p-10  w-[450px]  md:w-[650px] hover:scale-95 duration-300 leading-tight pt-30">
                    <h2 class=" uppercase font-thin border-t-2 ml-5 text-5xl font-thing text-amber-800 tracking-widest p-10">
                        Academics
                    </h2>
                        <h1 class="text-3xl text-gray-900 flex justify-between">Bachelor of Science in Computer Science <i class="text-sm text-gray-500 pt-3">2016 - 2020</i></h1>
                        <i class="text-gray-500 text-xl">St. John Technological College of the Philippines</i>
                        <!-- <ul class="list-disc  marker:text-black text-justify">
                            <li><p class="leading-tight">Develop and integrated APIs to support frontend components, ensuring smooth communication between the frontend and backend</p></li>
                            <li>Identified API Errors & Fixing. Debugged API responses, fixed backend-related errors, and optimized API efficiency for better performance.</li>
                        </ul> -->
                        <h1 class="flex justify-between text-3xl text-gray-900 pt-5">Computer Secretarial<i class="text-sm text-gray-500 pt-3">2008 - 2010</i></h1>
                        <i class="text-gray-500 text-xl">Datamex Institute of Computer Technology, Quezon City</i>
                        <!-- <ul class="list-disc leading-relaxed marker:text-black">
                            <li>Got deployed in a different project and created sidebar, revising UI to be responsive and implement it on their UI Web design</li>
                            <li>Output revision based on our clients and Team Lead desired</li>
                        </ul> -->
                    </div>
                </div>
            </section>
        </div>
</template>