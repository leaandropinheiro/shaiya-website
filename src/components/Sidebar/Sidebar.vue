<template>
    <div class="">
        <div class="flex lg:flex-row sm:flex-col md:flex-row flex-col gap-2 mx-auto max-w-screen-xl">
            <aside class="flex flex-col gap-2 sm:w-full md:w-3/12 lg:w-3/12 h-auto" aria-label="Sidebar">
                <login />
                <ServerStatus />
                <Discord />
            </aside>
            <aside class="lg:w-9/12 border backgroundBlur border-gray-700 sm:w-full md:w-9/12 rounded-xl h-auto" aria-label="Sidebar">
                <div class="">
                    <div class="text-left border-b border-gray-700">                        
                        <h2 class="px-4 py-2 text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Server Information</h2>
                    </div>
                    <div class="flex flex-col px-4 py-4">
                        <ServerDetails />   
                    </div>                 
                </div>
            </aside>
        </div>
    </div>
</template>
<script setup>
import ServerDetails from '../ServerDetails/ServerDetails.vue'
import Login from '../Login/Login.vue'
import ServerStatus from '../ServerStatus/ServerStatus.vue'
import Discord from '../Discord/Discord.vue'
</script>

