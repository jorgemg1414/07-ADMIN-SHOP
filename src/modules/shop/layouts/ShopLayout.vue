<script setup lang="ts">
import CustomFooter from '../components/CustomFooter.vue';
import TopMenu from '../components/TopMenu.vue';
import { RouterView } from 'vue-router';
</script>

<template>
  <!-- Header Navbar -->
  <TopMenu />

  <!-- Router View  -->
  <RouterView />
  <!-- Footer -->
  <CustomFooter />
</template>
