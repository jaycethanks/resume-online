<script lang="ts" setup>
import router from '@/router';
const currentPath = router.currentRoute.value.fullPath
</script>
<template>
  <div class="w-full h-screen flex justify-center items-center flex-col">
    <h1 class="text-[48px] font-bold">404</h1>
    <h1 class="text-lg font-bold">NOT FOUND : )</h1>
    <h2 class="mt-5">Have a coffee break ☕️, And have a nice day!</h2>
    <h3 class="mt-5">Current Path: {{ currentPath }}</h3>
  </div>
</template>
