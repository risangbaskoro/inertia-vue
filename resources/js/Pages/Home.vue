<script setup>
defineProps({
  laravelVersion: String
})
</script>

<template>
    <div>
        <h1>Laravel {{ laravelVersion }}</h1>
    </div>
</template>