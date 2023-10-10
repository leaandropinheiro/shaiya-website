<template>    
    <div class="flex flex-col gap-2 w-full border rounded-xl border-gray-700 backgroundBlur">
        <div class="text-center border-b border-gray-700 py-2">
            <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Account</h2>
        </div>
        <div class="text-center py-2">
            <p class="text-sm font-normal text-gray-500 dark:text-gray-400">Connect with your account.</p>
        </div>

        <div class="flex flex-col gap-4 px-2">
            <button class="flex items-center p-2 text-base font-bold rounded-lg hover:bg-gray-100 group hover:shadow bg-gray-600 hover:bg-gray-500 text-white">
                    <span class="flex-1 ml-2 whitespace-nowrap">Login</span>
            </button>

            <button class="flex items-center p-2 text-base font-bold rounded-lg hover:bg-gray-100 group hover:shadow bg-gray-600 hover:bg-gray-500 text-white">
                    <span class="flex-1 ml-2 whitespace-nowrap">Login</span>
            </button>
        </div>
        <div class="flex text-center items-center justify-center py-2">
            <a href="#" class="inline-flex items-center text-xs font-normal text-gray-500 hover:underline dark:text-gray-400">
                <svg class="w-3 h-3 mr-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7.529 7.988a2.502 2.502 0 0 1 5 .191A2.441 2.441 0 0 1 10 10.582V12m-.01 3.008H10M19 10a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
                </svg>
                Forget password ?
            </a>
        </div>
    </div>
</template>

<script setup> 

</script>

<style scoped>
</style>