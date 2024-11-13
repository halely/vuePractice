<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper ">
      <nav>
        <RouterLink to="/">家庭</RouterLink>
        <RouterLink to="/about">关于</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
