<template>
    <div class="bg-gray-800 top-4 flex w-full">
        <navbar class="flex items-center mb-8 mt-4">
            <!-- <img class="object-contain w-35 h-14" src="@/assets/image/pc1.jpg" alt="logo de tailwind"> -->
            <div class="text-green-600 font-burtons text-2xl ml-5 grid grid-cols-6 place-content-start">
                <NuxtLink to="/contact"><strong>CKF</strong></NuxtLink>
            </div>
            <div class="items-center flex space-x-6 flex">
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/apropos"><strong class="text-green-600">01. </strong>Apropos</NuxtLink>
                </div>
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/experience"><strong class="text-green-600">02. </strong>Experience</NuxtLink>
                </div>
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/projet"><strong class="text-green-600">03. </strong>Projet</NuxtLink>
                </div>
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/contact"><strong class="text-green-600">04. </strong>Contact</NuxtLink>
                </div>
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/resume"><strong class="text-green-600">05. </strong>Resumé</NuxtLink>
                </div>
                <div class="text-xs text-white font-bold">
                    <NuxtLink to="/vision"><strong class="text-green-600">06. </strong>Vision</NuxtLink>
                </div>
                <div class="text-xs justify-center text-white shadow border-2 px-2 border-green-600 brightness-200 h-6">
                    <a href="https://www.google.com/intl/fr/gmail/about/" class="items-center"><strong>foussenichourik@gmail.com</strong></a>
                </div>
            </div>
        </navbar>
    </div>
</template>