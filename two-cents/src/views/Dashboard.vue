<script setup lang="ts">
    defineProps<{ msg: string }>()
</script>

<template>
    <h1 class="italic font-bold hover:not-italic text-2xl"> {{ msg }} </h1>
</template>

<style scoped>

</style>