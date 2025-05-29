<template>
    <div class="min-h-screen flex flex-col items-center">
        <div class="mt-6 px-4 py-10 max-w-md bg-gradient-to-r from-blue-400 to-violet-600 rounded-xl">
            <h1 class="text-2xl font-semibold mb-8 text-white">Entre em contato:</h1>
            <form class="space-y-4">
                <input type="text" placeholder="Nome" class="w-full p-2 border rounded-md dark:bg-slate-700 dark:border-slate-600 dark:text-white" />
                <input type="email" placeholder="E-mail" class="w-full p-2 border rounded-md dark:bg-slate-700 dark:border-slate-600 dark:text-white" />
                <textarea placeholder="Texto" class="w-full p-2 border rounded-md dark:bg-slate-700 dark:border-slate-600 dark:text-white"></textarea>
                <div class="flex justify-end">
                    <button type="submit" class="bg-indigo-400 dark:bg-indigo-500 text-white px-4 py-2 border dark:border-indigo-800 rounded-lg shadow transition duration-300 transform hover:scale-105">Enviar</button>
                </div>
            </form>
        </div>
    </div>
</template>