<template></template>

<script setup>
definePageMeta({
    layout: "page",
});

useSeoMeta({
    title: "Home",
    // Ini ditimpa karena kita sudah setup title template nya di app vue, karena biasanya di halaman home kita tidak menggunakkan title template
    titleTemplate: "",
});
</script>

<style></style>
