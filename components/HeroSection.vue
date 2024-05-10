<template>
  <div :style="{ backgroundImage: `url(${image})` }" class="hero-container relative">
    <!-- Tint overlay -->
    <div class="absolute inset-0 bg-gull-gray-800 opacity-50"></div>

    <!-- Content -->
    <div class="container mx-auto px-4 py-8 relative z-10 text-white">
      <slot></slot>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    image: { type: String, required: true }
  }
}
</script>

<style scoped>
/* Styles for the hero container */
.hero-container {
  position: relative;
  height: 400px; /* Adjust the height as needed */
  background-size: cover;
  background-position: center;
}

/* Tint overlay */
.hero-container .opacity-50 {
  /* Adjust opacity and color as needed */
}

/* Styles for the content */
.container {
  position: relative;
}
</style>
