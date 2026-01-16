<script setup lang="ts">
interface Skill {
  name: string
}

const skills: Skill[] = [
  { name: 'JavaScript' },
  { name: 'TypeScript' },
  { name: 'Vue.js' },
  { name: 'React.js' },
  { name: 'HTML/CSS' },
  { name: 'C#' }
]
</script>

<template>
  <section id="experience">
    <div class="sticky-header">
      <h2 class="lightText">Experience</h2>
    </div>

    <div class="experience-contents">
      <div class="experience-card">
        <p class="tenure">2024 - Present</p>

        <div class="card-column">
          <h3 class="anchor-text card-header">
            Software Engineer: Frontend · Capitec Bank
          </h3>

          <p>
            Designing and maintaining client-facing applications for
            Self Service Terminals using Vue, React and TypeScript.
          </p>

          <div class="tag-container">
            <div v-for="skill in skills" :key="skill.name" class="tag">
              {{ skill.name }}
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
