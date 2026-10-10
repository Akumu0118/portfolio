<script setup lang="ts">
</script>

<template>
  <section class="flex flex-col items-center justify-center text-center py-8 md:py-12 px-4">
    <!-- Profile Picture -->
    <div class="w-40 h-40 sm:w-48 sm:h-48 md:w-56 md:h-56 rounded-full border-4 border-[#1b9986] overflow-hidden shadow-2xl mb-6">
      <img 
        src="/profile.jpg" 
        alt="Profile Picture" 
        class="w-full h-full object-cover" 
      />
    </div>
    
    <!-- Name and Title -->
    <h1 class="text-3xl sm:text-4xl md:text-5xl font-extrabold text-[#1b9986] mb-3 tracking-tight">
      Miguel Joseph Sean M. Tumaliuan
    </h1>
    <p class="text-xl sm:text-2xl text-gray-700 font-bold">
      Computer Engineering Student
    </p>
  </section>
</template>

<style scoped>
</style>