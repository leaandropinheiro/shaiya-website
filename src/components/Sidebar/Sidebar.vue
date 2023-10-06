<template>
    <div class="">
        <div class="flex lg:flex-row sm:flex-col md:flex-row flex-col gap-2 mx-auto max-w-screen-xl">
            <aside class="lg:w-9/12 border border-gray-700 sm:w-full md:w-9/12 rounded-xl h-auto" aria-label="Sidebar">
                <div class="">
                    <div class="text-left border-b border-gray-700">                        
                        <h2 class="px-4 py-2 text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Server Information</h2>
                    </div>
                    <div class="flex flex-col px-4 py-4">
                        <ServerDetails />   
                    </div>                 
                </div>
            </aside>
            <aside class="lg:w-3/12 border border-gray-700 sm:w-full md:w-3/12 rounded-xl h-screen" aria-label="Sidebar">
                <div class="">
                    <div class="">
                    <div class="text-center border-b border-gray-700">                        
                        <h2 class="px-4 py-2 text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Account</h2>
                    </div>
                </div>
                </div>
            </aside>
        </div>
    </div>
</template>

<script setup>
import ServerDetails from '../ServerDetails/ServerDetails.vue'
</script>

