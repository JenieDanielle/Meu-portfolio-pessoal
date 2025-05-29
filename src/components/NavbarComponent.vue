<template>
    <nav class="py-4 px-8 flex items-center justify-between">
        <div class="text-lg font-bold">
            <h1 class="text-indigo-900">Meu Portfólio</h1>
        </div>
        <div>
            <ul class="flex gap-6 mx-auto">
                <li><router-link to="/" class="hover:underline text-indigo-800">Início</router-link></li>
                <li><router-link to="/about" class="hover:underline text-indigo-800">Sobre</router-link></li>
                <li><router-link to="/contact" class="hover:underline text-indigo-800">Contato</router-link></li>
            </ul>
        </div>
        <!-- <div class="w-24"></div> -->

        <div class="flex gap-6 text-center">
            <a href="https://www.linkedin.com/in/jeniedanielle/" class="flex flex-col text-center text-blue-900">
                <i class="bi bi-linkedin "></i> 
            </a>
            <a href="https://www.linkedin.com/in/jeniedanielle/" class="flex flex-col text-center text-blue-900">
                <i class="bi bi-github"></i> 
            </a>
        </div>
    </nav>
</template>