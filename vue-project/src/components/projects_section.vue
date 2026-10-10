<script setup lang="ts">
// You can customize or pass props for your projects here
</script>

<template>
  <section class="mb-16 px-4 sm:px-0">
    <h2 class="text-3xl sm:text-4xl font-extrabold text-[#1b9986] mb-8 text-center">
      Featured Projects
    </h2>
    
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      
      <!-- Project Card 1 -->
      <div class="bg-white rounded-xl shadow-md overflow-hidden border border-[#1b9986]/20 hover:shadow-xl transition duration-300 flex flex-col justify-between">
        <div class="p-6">
          <div class="flex justify-between items-center mb-3">
            <h3 class="text-xl font-bold text-gray-800">Embedded IoT Sensor Hub</h3>
            <span class="text-xs font-semibold bg-[#c4fff0] text-[#1b9986] px-3 py-1 rounded-full">Hardware</span>
          </div>
          <p class="text-gray-600 text-sm sm:text-base mb-4">
            Designed a custom PCB layout and wrote modular Arduino/C code to gather environmental sensor data and transmit it over SPI/I2C communication protocols.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">Arduino</span>
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">C++</span>
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">PCB Design</span>
          </div>
        </div>
      </div>

      <!-- Project Card 2 -->
      <div class="bg-white rounded-xl shadow-md overflow-hidden border border-[#1b9986]/20 hover:shadow-xl transition duration-300 flex flex-col justify-between">
        <div class="p-6">
          <div class="flex justify-between items-center mb-3">
            <h3 class="text-xl font-bold text-gray-800">PIC Microcontroller System</h3>
            <span class="text-xs font-semibold bg-[#c4fff0] text-[#1b9986] px-3 py-1 rounded-full">Embedded</span>
          </div>
          <p class="text-gray-600 text-sm sm:text-base mb-4">
            Developed low-level firmware utilizing Micro C programming, handling real-time interrupt requests and precise hardware timing control.
          </p>
          <div class="flex flex-wrap gap-2">
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">Micro C</span>
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">PIC Microcontroller</span>
            <span class="text-xs bg-gray-100 text-gray-700 px-2.5 py-1 rounded">Systems</span>
          </div>
        </div>
      </div>

    </div>
  </section>
</template>

<style scoped>
</style>