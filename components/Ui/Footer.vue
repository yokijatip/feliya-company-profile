<template>
    <footer class="border-t bg-blue-950">
        <div>
            <div
                class="footer max-w-full text-white p-10 flex flex-col md:flex-row justify-evenly"
            >
                <aside>
                    <img src="/public/images/feliya.png" class="h-24" />
                    <p>
                        <span class="footer-title text-4xl inline-block mb-4"
                            >Feliya Laju Teknik</span
                        >
                    </p>
                    <div>
                        <h1 class="text-xl font-semibold">
                            Jl. Pemuda No. 1, Jakarta
                        </h1>
                        <h1 class="text-lg font-thin">08-12345678</h1>
                        <h1 class="text-lg font-thin">k9iXU@example.com</h1>
                    </div>
                </aside>
                <div class="flex md:flex-row flex-col md:gap-28 gap-10">
                    <nav class="flex flex-col gap-2">
                        <h6 class="footer-title">Layanan</h6>
                        <a
                            class="link link-hover"
                            v-for="service in services"
                            :key="service"
                            >{{ service.name }}</a
                        >
                    </nav>
                    <nav class="flex flex-col gap-2">
                        <h6 class="footer-title">Company</h6>
                        <a
                            class="link link-hover"
                            v-for="menu in companyMenu"
                            :key="menu"
                            >{{ menu.name }}</a
                        >
                    </nav>
                    <nav class="flex flex-col gap-2">
                        <h6 class="footer-title">Sosial Media</h6>
                        <a
                            class="link link-hover"
                            v-for="social in socialMedia"
                            :key="social"
                            >{{ social.name }}</a
                        >
                    </nav>
                </div>
            </div>
        </div>
    </footer>
</template>

<script setup>
const socialMedia = ref([
    {
        name: "Facebook",
    },
    {
        name: "Instagram",
    },
    {
        name: "Whatsapp",
    },
]);

const companyMenu = ref([
    {
        name: "Home",
    },
    {
        name: "About us",
    },
    {
        name: "Contact",
    },
    {
        name: "Mengapa Memilih Kami",
    },
]);

const services = ref([
    {
        name: "Air Conditioner",
    },
    {
        name: "Air Dryer",
    },
    {
        name: "Air Purifier",
    },
    {
        name: "Refrigerasi",
    },
]);
</script>
