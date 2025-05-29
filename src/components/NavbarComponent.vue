<template>
    <nav class="py-4 px-8 flex items-center justify-between dark:bg-gray-900 border-b-2 border-gray-200 dark:border-gray-700">
        <div class="text-lg font-bold">
            <h1 class="text-indigo-900 dark:text-white">Meu Portfólio</h1>
        </div>
        <div>
            <ul class="flex gap-6 mx-auto">
                <li><router-link to="/" class="hover:underline text-indigo-800 dark:text-indigo-100">Início</router-link></li>
                <li><router-link to="/about" class="hover:underline text-indigo-800 dark:text-indigo-100">Sobre</router-link></li>
                <li><router-link to="/contact" class="hover:underline text-indigo-800 dark:text-indigo-100">Contato</router-link></li>
            </ul>
        </div>
        <!-- <div class="w-24"></div> -->

        <div class="flex gap-6 text-center">
            <button @click="toggleDark" class="flex items-center gap-2 px-4 py-2 bg-indigo-500 dark:bg-indigo-400 text-white dark:text-white rounded-full hover:scale-105 transition">
                <span v-if="isDark"><i class="bi bi-sun-fill"></i></span>
                <span v-else><i class="bi bi-moon-stars"></i></span>
            </button>
        </div>
    </nav>
</template>
<script>
export default {
    data() {
        return {
            isDark: false,
        };
    },
    mounted() {
        this.isDark = document.documentElement.classList.contains('dark');
    },
    methods: {
        toggleDark() {
            document.documentElement.classList.toggle('dark')
            this.isDark = !this.isDark
        }
    }
}
</script>