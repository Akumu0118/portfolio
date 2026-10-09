<script setup lang = "ts">
</script>

<template>
  <section class="flex flex-col items-center justify-center text-center py-12">
    <!-- Profile Picture called directly from the public folder -->
    <div class="w-56 h-56 rounded-full border-4 border-[#1b9986] overflow-hidden shadow-2xl mb-6">
      <img 
        src="/profile.jpg" 
        alt="Profile Picture" 
        class="w-full h-full object-cover" 
      />
    </div>
    
    <!-- Name and Title placed directly inside tags -->
    <h1 class="text-5xl font-extrabold text-[#1b9986] mb-3 tracking-tight">
      Miguel Joseph Sean M. Tumaliuan
    </h1>
    <p class="text-2xl text-gray-700 font-bold">
      Computer Engineering Student
    </p>
  </section>
</template>

<style scoped>
</style>