<template>
    <div class="min-h-screen bg-gray-50 text-gray-800 flex flex-col">
        <!-- Header -->
        <UiHeader />

        <!-- Content -->
        <main class="flex-1 flex">
            <slot />
        </main>

        <!-- Footer -->
        <UiFooter />
    </div>
</template>
