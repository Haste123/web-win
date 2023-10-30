<script setup lang="ts">
import {onMounted, ref, withDirectives} from "vue"

const menus = []
for (let i = 0; i < 1200; i++) {
  let temp = {id: i,name:i}
  menus.push(temp)
}
</script>

<template>
  <div class="h-90 bg-amber-100 flex flex-row flex-wrap">
    <div class="h-5 w-max bg-blue-300 ml-3 " v-for="item in menus">{{item}}</div>
  </div>
</template>

<style scoped>
.h-90 {
  height: 95%;
}
</style>