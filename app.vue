<template>
    <div>
        <NuxtRouteAnnouncer />
        <NuxtLayout>
            <NuxtPage />
        </NuxtLayout>
    </div>
</template>

<script setup>
useSeoMeta({
    // Bikin Suffix dengan cara ribet
    // titleTemplate: (title) => {
    //     return title ? `${title} | YokiJP` : "YokiJP";
    // },

    // Bikin Suffix dengan cara simple
    titleTemplate: "%s | YokiJP",
});
</script>
