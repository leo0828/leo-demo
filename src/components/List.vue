<template>
    <div class="my-list">
        <ListItem v-for="(i, k) in list" :title="i.title" :path="i.path" />
    </div>
</template>

<script setup>
import ListItem from './ListItem.vue';
const list = [{
    title: 'Three.js应用',
    path: '/three',
}]
</script>
<style></style>