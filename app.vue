<template>
  <UCard :ui="ui">
    <template #header> <Navigation /> </template>

    <RouterView />

    <template #footer> This is my footer </template>
  </UCard>
</template>

<script setup lang="ts">
import Navigation from "./components/Navigation.vue";

const ui = reactive({
  base: "overflow-hidden min-h-screen",
  background: "bg-white dark:bg-gray-900",
  divide: "divide-y divide-gray-200 dark:divide-gray-800",
  ring: "ring-1 ring-gray-200 dark:ring-gray-800",
  rounded: "rounded-lg",
  shadow: "shadow",
  body: {
    base: "",
    background: "",
    padding: "p-4 sm:p-6",
  },
  header: {
    base: "",
    background: "",
    padding: "p-4 sm:px-6",
  },
  footer: {
    base: "absolute bottom-0 left-0 right-0",
    background: "",
    padding: "p-4 sm:px-6",
  },
});
</script>

<style scoped></style>
