<template>
    <div class="my-list-item">
        <RouterLink :to="path">{{ title }}</RouterLink>
    </div>
</template>

<script setup>
defineProps(['title', 'path']);
</script>

<style></style>