<template>
    <div>
      <div class="flex">
        <Sidebar />
        <div class="flex-1">
          <!-- Main content goes here -->
          <slot />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import Sidebar from '@/Components/Sidebar.vue';
  
  export default {
    components: {
      Sidebar,
    },
  };
  </script>
  
  <style>
  </style>
  