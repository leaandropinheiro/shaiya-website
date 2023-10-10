<template> 
    <nav class=" bg-gray-800 border-b border-gray-700">
        <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4 ">
            <a href="https://flowbite.com/" class="flex items-center">
                <img src="" class="h-8 mr-3" alt="" />
                <span class="self-center text-2xl font-semibold whitespace-nowrap text-gray-400">Shaiya</span>
            </a>
            <div class="flex md:order-2">
                <button type="button" class="text-white focus:ring-4 focus:outline-none font-medium rounded-lg text-sm px-4 py-2 text-center mr-3 md:mr-0 bg-blue-600 hover:bg-blue-800 focus:ring-blue-800">Get started</button>
                <button data-collapse-toggle="navbar-cta" type="button" id="btnMenu" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 dark:text-gray-400 dark:hover:bg-gray-800 dark:focus:ring-gray-600" aria-controls="navbar-cta" aria-expanded="false">
                    <span class="sr-only">Open main menu</span>
                    <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
                    </svg>
                </button>
            </div>
            <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-cta">
                <ul class="flex flex-col font-medium p-4 md:p-0 mt-4 border rounded-lg md:flex-row md:space-x-8 md:mt-0 md:border-0 bg-gray-900 md:bg-gray-800 border-gray-700">
                    <li>
                        <a href="#" class="block py-2 pl-3 pr-4 bg-blue-800 rounded md:bg-transparent md:text-blue-800 md:p-0" aria-current="page">Home</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pl-3 pr-4 md:hover:text-blue-800 md:p-0 text-white hover:bg-gray-800 hover:text-white md:hover:bg-transparent border-gray-700">About</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pl-3 pr-4 md:hover:text-blue-800 md:p-0 text-white hover:bg-gray-800 hover:text-white md:hover:bg-transparent border-gray-700">Services</a>
                    </li>
                    <li>
                        <a href="#" class="block py-2 pl-3 pr-4 md:hover:text-blue-800 md:p-0 text-white hover:bg-gray-800 hover:text-white md:hover:bg-transparent border-gray-700">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

</template>

<script setup>
document.addEventListener('DOMContentLoaded', function () {
const btnMenu = document.getElementById('btnMenu');
const navbarCta = document.getElementById('navbar-cta');

btnMenu.addEventListener('click', function () {
    const isExpanded = navbarCta.getAttribute('aria-expanded') === 'true';
    
    navbarCta.setAttribute('aria-expanded', !isExpanded);
    navbarCta.classList.toggle('hidden');
});
});


</script>


<style scoped>


</style>