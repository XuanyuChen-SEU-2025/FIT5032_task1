<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <section class="welcome">
    <h1>{{ msg }}</h1>
    <p>
      You have successfully created a Vue.js project with Vite. This page keeps the
      main welcome content visible while adding the assessed lab component below.
    </p>
    <p>
      Visit
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Vue documentation</a>
      to learn more about Vue.
    </p>
  </section>
</template>

<style scoped>
.welcome {
  text-align: center;
}

h1 {
  color: #42b883;
  font-size: 2.4rem;
  margin: 0 0 1rem;
}

p {
  color: #2c3e50;
  line-height: 1.6;
  margin: 0.5rem 0;
}

a {
  color: #42b883;
}
</style>
