<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavbarComponent from './components/NavbarComponent.vue';
</script>

<template>

  <header>
      <nav>
          <NavbarComponent />
      </nav>
  </header>
  <RouterView />

</template>

