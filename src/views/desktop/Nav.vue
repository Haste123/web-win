<script setup lang="ts">
import beginMenu from '@/assets/img/desktop/begin_menu.png'
import search from '@/assets/img/desktop/search.png'
</script>

<template>
  <div class="h-10 bg-amber-300 flex justify-center items-center">
    <img :src="beginMenu" class="w-7 h-7" alt="开始"/>
    <p>
      <img :src="search" class="w-3 h-3 inline-block left-5 relative" alt="搜索"/>
      <input class="ml-1 pl-5 p-1 inline-block rounded placeholder:text-black placeholder:text-xs box-content focus:outline-blue-300" placeholder="搜索"/>
    </p>
  </div>
</template>

<style scoped>
.h-10{
  height: 5%;
}
</style>