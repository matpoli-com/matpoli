<template>
    {{slug}}
</template>

<script setup lang="ts">
const route = useRoute();
const slug = route.params.slug
</script>