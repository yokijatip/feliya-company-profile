<template>
    <div class="min-h-screen bg-white flex flex-col">
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
