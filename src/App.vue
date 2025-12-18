<template>
  <!--<Header title="骤雨重山图床" desc="" />-->
  <main><RouterView /></main>
  <Footer />
  <Toaster />
</template>
<script setup lang="ts">
// import Header from '@/components/Header/Header.vue';
import Footer from '@/components/Footer/Footer.vue';
import { Toaster } from '@/components/ui/toast';
</script>

<style scoped></style>
