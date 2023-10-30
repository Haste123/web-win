<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import content from "@/views/desktop/Content.vue"
import myNav from "@/views/desktop/Nav.vue"
</script>

<template>
  <div class="w-screen h-screen absolute overflow-hidden">
    <content class="relative top-0"/>
    <my-nav class="relative bottom-0"/>
  </div>
</template>

<style scoped>
</style>
