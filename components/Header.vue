<template>
    <div class="bg-white pb-0">
        <div class="max-w-screen-2xl px-4 md:px-8 mx-auto bg-sky-300">
            <header class="flex justify-between items-center md:py-8">
            <div class="border border-slate-300 hover:border-slate-400 rounded-lg border-2 p-2">
                <NuxtLink to="/" class="inline-flex items-center text-black-800 text-3xl md:text-3xl font-bold gap-2.5" aria-label="logo">
                    おしゃれボタン
                </NuxtLink>
            </div>
            <nav class="hidden lg:flex gap-12">
                <NuxtLink to="/" class="text-gray-600 hover:text-teal-500 active:text-teal-700 text-2xl font-bold transition duration-100">index</NuxtLink>
                <NuxtLink to="/subpage" class="text-gray-600 hover:text-teal-500 active:text-teal-700 text-2xl font-bold transition duration-100">subpage</NuxtLink>
                <NuxtLink to="/" class="text-gray-600 hover:text-teal-500 active:text-teal-700 text-2xl font-bold transition duration-100">index</NuxtLink>
                <NuxtLink to="/subpage" class="text-gray-600 hover:text-teal-500 active:text-teal-700 text-2xl font-bold transition duration-100">subpage</NuxtLink>
                <NuxtLink to="/" class="text-gray-600 hover:text-teal-500 active:text-teal-700 text-2xl font-bold transition duration-100">index</NuxtLink>
            </nav>
            <a href="#" class="hidden lg:inline-block bg-gray-200 hover:bg-gray-300 focus-visible:ring ring-teal-300 text-gray-500 active:text-gray-700 text-2xl md:text-2xl font-bold text-center rounded-lg outline-none transition duration-100 px-4 py-2">おしゃれボタン2</a>
            </header>
        </div>
    </div>
</template>
