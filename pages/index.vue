<template>
    <div class="flex flex-col flex-1">
        <!-- Hero Section -->
        <section
            class="relative flex justify-center items-center min-h-[calc(100vh-68px)] bg-cover bg-center bg-no-repeat"
            style="
                background-image: url('https://us.images.westend61.de/0001342695pw/worker-repairing-air-conditioner-EYF00957.jpg');
            "
        >
            <!-- Overlay -->
            <div class="absolute inset-0 bg-black/50"></div>

            <!-- Text di tengah -->
            <div class="relative z-10 text-center text-white">
                <h1 class="text-4xl font-bold mx-auto">
                    Perusahaan AC dan pendingin <br />
                    yang Terpercaya
                </h1>
                <p class="text-lg mt-2 w-1/2 mx-auto">
                    Di PT Feliya Laju Teknik , kami dapat memberi Anda berbagai
                    layanan untuk kebutuhan AC dan pendingin Anda. Kami berbasis
                    di Jakarta, Indonesia dan mencakup Jabodetabek, Bandung, dan
                    daerah sekitarnya.
                </p>
                <UButton
                    class="mt-4"
                    color="orange"
                    size="xl"
                    style="color: white"
                    >Lihat Layanan Kami</UButton
                >
            </div>
        </section>

        <!-- 3 Quality -->
        <!-- Quality, Free Consultation, Fully Qualified -->
        <section class="">
            <!--  Container  -->
            <div class="container mx-auto">
                <!--  Container Item  -->
                <div
                    class="flex gap-4 justify-evenly md:flex-row flex-col items-center md:h-full p-4 bg-biruDongker text-white"
                >
                    <!-- Item 1  -->
                    <div class="flex items-center gap-4">
                        <svg
                            class="w-6 h-6"
                            stroke-width="1.5"
                            viewBox="0 0 24 24"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                            color="#ffffff"
                        >
                            <path
                                d="M1 20V19C1 15.134 4.13401 12 8 12V12C11.866 12 15 15.134 15 19V20"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                            ></path>
                            <path
                                d="M13 14V14C13 11.2386 15.2386 9 18 9V9C20.7614 9 23 11.2386 23 14V14.5"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                            ></path>
                            <path
                                d="M8 12C10.2091 12 12 10.2091 12 8C12 5.79086 10.2091 4 8 4C5.79086 4 4 5.79086 4 8C4 10.2091 5.79086 12 8 12Z"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            ></path>
                            <path
                                d="M18 9C19.6569 9 21 7.65685 21 6C21 4.34315 19.6569 3 18 3C16.3431 3 15 4.34315 15 6C15 7.65685 16.3431 9 18 9Z"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            ></path>
                        </svg>

                        <p class="text-md">Pengerjaan Berkualitas</p>
                    </div>

                    <!-- Item 2  -->
                    <div class="flex items-center gap-4">
                        <svg
                            class="w-6 h-6"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                            color="#ffffff"
                        >
                            <path
                                d="M8.5 4H6C4.89543 4 4 4.89543 4 6V20C4 21.1046 4.89543 22 6 22H12"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                            ></path>
                            <path
                                d="M15.5 4H18C19.1046 4 20 4.89543 20 6V15"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                            ></path>
                            <path
                                d="M8 6.4V4.5C8 4.22386 8.22386 4 8.5 4C8.77614 4 9.00422 3.77604 9.05152 3.50398C9.19968 2.65171 9.77399 1 12 1C14.226 1 14.8003 2.65171 14.9485 3.50398C14.9958 3.77604 15.2239 4 15.5 4C15.7761 4 16 4.22386 16 4.5V6.4C16 6.73137 15.7314 7 15.4 7H8.6C8.26863 7 8 6.73137 8 6.4Z"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                            ></path>
                            <path
                                d="M15.5 20.5L17.5 22.5L22.5 17.5"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            ></path>
                        </svg>
                        <p class="text-md">Konsultasi Gratis</p>
                    </div>

                    <!-- Item 1  -->
                    <div class="flex items-center gap-4">
                        <svg
                            class="w-6 h-6"
                            stroke-width="1.5"
                            viewBox="0 0 24 24"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                            color="#ffffff"
                        >
                            <path
                                d="M3 20.4V3.6C3 3.26863 3.26863 3 3.6 3H20.4C20.7314 3 21 3.26863 21 3.6V20.4C21 20.7314 20.7314 21 20.4 21H3.6C3.26863 21 3 20.7314 3 20.4Z"
                                stroke="#ffffff"
                                stroke-width="1.5"
                            ></path>
                            <path
                                d="M15 8.5C14.315 7.81501 13.1087 7.33855 12 7.30872M9 15C9.64448 15.8593 10.8428 16.3494 12 16.391M12 7.30872C10.6809 7.27322 9.5 7.86998 9.5 9.50001C9.5 12.5 15 11 15 14C15 15.711 13.5362 16.4462 12 16.391M12 7.30872V5.5M12 16.391V18.5"
                                stroke="#ffffff"
                                stroke-width="1.5"
                                stroke-linecap="round"
                                stroke-linejoin="round"
                            ></path>
                        </svg>
                        <p class="text-md">Harga Terjangkau</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section></section>
    </div>
</template>

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
