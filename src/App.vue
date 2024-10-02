<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="header">
    <nav>
      <a href="/">Go to Home</a>
      <a href="/about">Go to About</a>
    </nav>
  </div>
  <div class="google-map">
    <h2>Google Map</h2>
    <iframe width="100%" height="300" frameborder="0" style="border: 0" src="https://www.google.com/maps/embed/v1/place?key=AIzaSyDy7IM3QB1oEz9kNgJsTb7zyF-5djQ4iJk&q=Eiffel+Tower,Paris+France"></iframe>
  </div>
  <RouterView />
</template>

<style scoped>
.header {
  width: 100%;
}

.header a {
  border: 1px solid #ffffff65;
  margin-right: 12px;
  padding: 8px;
}

.google-map {
  width: 100%;
}

</style>
