<script setup>
import HeroSection from './components/hero_section.vue'
import AboutMe from './components/about_me.vue'
import SkillsSection from './components/skills_section.vue'
</script>

<template>
  <!-- Main Background Container -->
  <div class="min-h-screen bg-[#c4fff0] font-sans text-gray-900 pb-12">
    
    <main class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 pt-10 space-y-12">
      <HeroSection />
      <AboutMe />
      <SkillsSection />
    </main>
    
  </div>
</template>

<style scoped>
</style>