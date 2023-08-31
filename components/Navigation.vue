<template>
  <div class="container mx-auto px-2">
    <nav class="grid grid-col-8 gap-4 items-center">

      <div class="col-span-1">Sagar's Personal Website</div>

      <ul class="col-start-3 flex gap-4">
        <li>
            <NuxtLink to="/">About Me</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/projects">Projects</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/hobbies">Hobbies</NuxtLink>
        </li>
        <li>
            <NuxtLink to="/journey">Journey So Far</NuxtLink>
        </li>
      </ul>

      <div class="col-end-9 col-span-1">LinkedIn + Github</div>

    </nav>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
