<template>
  <v-app>
    <NavBar />
    <v-main>
      <slot />
    </v-main>
  </v-app>
</template>

<script setup lang=\"ts\">
import NavBar from '@/Components/NavBar.vue'
</script>

