<script setup lang="ts">
</script>

<template>
  <section class="bg-white rounded-2xl shadow-xl p-6 sm:p-8 md:p-12 mb-16">
    <h2 class="text-3xl sm:text-4xl md:text-5xl font-extrabold text-[#1b9986] border-[#1b9986] inline-block pb-2">
      About Me
    </h2>
    
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12 items-stretch py-8 md:py-12">
      
      <!-- Left Side: Description -->
      <div class="space-y-4 md:space-y-5 text-gray-700 text-base md:text-lg leading-relaxed flex flex-col justify-center">
        <p class="text-xl sm:text-2xl font-medium">
          Hi, I'm a Computer Engineering Student who loves to work with Embedded System Projects such as Circuit Designing, PCB layouting, and Hardware Integration.
        </p>
        <p class="text-xl sm:text-2xl font-medium">
          Aside from that, I also love playing songs, singing, cooking, and playing online games such as Mobile Legends, Dota, Dinostorm, and Clash of Clans.
        </p>
      </div>

      <!-- Right Side: Contact Information & CV -->
      <div class="bg-[#c4fff0] rounded-xl p-6 sm:p-8 shadow-inner border border-[#1b9986]/25 flex flex-col justify-between h-full">
        <div>
          <h3 class="text-xl sm:text-2xl font-bold text-[#1b9986] mb-6">Contact Info</h3>
          <ul class="space-y-4 text-gray-800 text-sm sm:text-base">
            <li class="flex flex-col sm:flex-row sm:items-start">
              <span class="font-bold w-28 shrink-0 mb-1 sm:mb-0">Gmail:</span>
              <a href="mailto:migueltumaliuan@gmail.com" class="hover:text-[#1b9986] transition-colors break-all">migueltumaliuan@gmail.com</a>
            </li>
            <li class="flex flex-col sm:flex-row sm:items-start">
              <span class="font-bold w-28 shrink-0 mb-1 sm:mb-0">Phone:</span>
              <a href="tel:+639653101173" class="hover:text-[#1b9986] transition-colors">09653101173</a>
            </li>
            <li class="flex flex-col sm:flex-row sm:items-start">
              <span class="font-bold w-28 shrink-0 mb-1 sm:mb-0">LinkedIn:</span>
              <a href="https://www.linkedin.com/in/miguel-joseph-sean-tumaliuan-4a9009393" class="hover:text-[#1b9986] transition-colors break-all">Miguel Joseph Sean Tumaliuan</a>
            </li>
            <li class="flex flex-col sm:flex-row sm:items-start">
              <span class="font-bold w-28 shrink-0 mb-1 sm:mb-0">Facebook:</span>
              <a href="https://www.facebook.com/share/18XM4aJPEu/" class="hover:text-[#1b9986] transition-colors break-all">Miguel Joseph Sean Tumaliuan</a>
            </li>
          </ul>
        </div>
        
       <!-- Download CV Button -->
        <a 
          href="/Tumaliuan, Miguel Joseph Sean M. - CV RESUME (2).pdf"
          download="Tumaliuan, Miguel Joseph Sean M. - CV RESUME (2).pdf"
          class="mt-8 w-full py-3 bg-[#1b9986] text-white text-base sm:text-lg font-semibold rounded-lg shadow-md hover:bg-[#147869] transform hover:-translate-y-1 transition duration-300 block text-center"
        >
          Download CV
        </a>
      </div> 
      
    </div> 
  </section>
</template>

<style scoped>
</style>