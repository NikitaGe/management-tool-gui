<script setup lang="ts">
import { ref } from "vue";

const items = ref([
    {
        label: 'Dashboard',
        icon: 'pi pi-home'
    },
    {
        label: 'Customers',
        icon: 'pi pi-address-book'
    },
    {
        label: 'Projects',
        icon: 'pi pi-list',
    },
]);
</script>

<template>
 <Menubar :model="items">
  <template #start>
    <div class="bg-indigo-500">
      <h2 class="mb-1">FastConnect</h2>
    </div>
  </template>

 </Menubar>
</template>
