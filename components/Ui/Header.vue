<script setup>
const menus = ref([
    {
        label: "Home",
        to: "/",
    },
    {
        label: "About",
        to: "/about",
    },
    {
        label: "Contact",
        to: "/contact",
    },
]);
</script>

<template>
    <header
        class="sticky top-0 w-full z-30 backdrop-blur-md shadow-lg shadow-gray-200 h-[68px] flex"
    >
        <PageContainer class="flex-1 flex items-center justify-between">
            <NuxtLink to="/" class="">
                <NuxtImg src="/feliya-transparent.svg" class="h-16 w-auto" />
            </NuxtLink>

            <!-- Nav Menu Using Variabel Menus in Script Setup -->
            <div class="divide-x-2 flex gap-4 divide-gray-500/50 items-center">
                <!-- Menus -->
                <nav class="pr-4">
                    <ul class="flex gap-4">
                        <li v-for="(menu, i) in menus" :key="i">
                            <NuxtLink
                                :to="menu.to"
                                class="hover:text-orange-500 transition-colors duration-300"
                                >{{ menu.label }}</NuxtLink
                            >
                        </li>
                    </ul>
                </nav>
            </div>
        </PageContainer>
    </header>
</template>
