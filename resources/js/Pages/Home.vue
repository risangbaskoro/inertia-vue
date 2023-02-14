<script setup>
defineProps({
  laravelVersion: String
})
</script>

<template>
  <div class="h-screen flex justify-center items-center">
    <h1 class="font-bold text-2xl">
      Laravel {{ laravelVersion }}
    </h1>
  </div>
</template>