<script setup>
import {BoltIcon} from "@heroicons/vue/24/outline";

defineProps({
  laravelVersion: String,
})
</script>

<template>
  <div class="h-screen flex justify-center items-center space-x-6">
    <BoltIcon class="h-12 w-12 text-indigo-500"/>
    <h1 class="font-bold text-2xl">
      Laravel {{ `v${laravelVersion}` }}
    </h1>
  </div>
</template>