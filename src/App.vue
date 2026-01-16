<script setup lang="ts">
import AppHeader from './components/AppHeader.vue'
import AboutSection from './components/AboutSection.vue'
import ExperienceSection from './components/ExperienceSection.vue'
import ProjectsSection from './components/ProjectsSection.vue'
import AppFooter from './components/AppFooter.vue'
</script>

<template>
  <!-- NO WRAPPER DIV -->
  <div class="underlay"></div>

  <AppHeader />

  <main>
    <AboutSection />
    <ExperienceSection />
    <ProjectsSection />
  </main>

  <AppFooter />
</template>

