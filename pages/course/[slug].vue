<template>
    {{slug}}
</template>

<script setup>
const route = useRoute();
const slug = route.params.slug
</script>