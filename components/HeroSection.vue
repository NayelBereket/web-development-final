<template>
    <div>
      <HeroSection image="/Users/lenovo/Downloads/Skilled Strings Logo.png">
        <h1 class="text-4xl font-bold mb-4">Welcome to Skilled Strings</h1>
        <p class="text-lg mb-8">Learn guitar from experienced tutors in your local area.</p>
        <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded">
          Get Started
        </button>
      </HeroSection>
    </div>
  </template>
  
  <script>
  import HeroSection from '@/components/HeroSection.vue'
  
  export default {
    components: {
      HeroSection
    }
  }
  </script>
  