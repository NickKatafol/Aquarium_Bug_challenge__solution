<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="app-wrapper">
    <nav>
      <div>
        <RouterLink to="/">Challenge</RouterLink>
        |
        <RouterLink to="/about">About the progect</RouterLink>
      </div>
    </nav>

    <RouterView />
  </div>
</template>

<style scoped>
.app-wrapper {
  width: 100%;
  max-width: 800px;
  margin: 0 auto;
  padding-bottom: 40px;
}

nav {
  border-bottom: gray 1px solid;
  padding: 6px 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
