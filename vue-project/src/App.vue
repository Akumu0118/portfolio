<script setup lang="ts">
import HeroSection from './components/hero_section.vue'
import AboutMe from './components/about_me.vue'
import SkillsSection from './components/skills_section.vue'
import Projects from './components/projects_section.vue'
import Header from './components/header.vue'
</script>

<template>
  <div class="min-h-screen bg-[#c4fff0] font-sans text-gray-900 pb-12 overflow-x-hidden">
    <main class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 pt-6 sm:pt-10 space-y-8 sm:space-y-12">
      <Header />
      <HeroSection />
      <AboutMe />
      <SkillsSection />
      <Projects />
    </main>
  </div>
</template>
