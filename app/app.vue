<script setup lang="ts">
import "~/assets/css/global.css";
import SheetProvider from "~/providers/SheetProvider.vue";
</script>

<template>
  <NuxtLayout>
    <NuxtPage />

    <Toaster />
    <SheetProvider />
  </NuxtLayout>
</template>
