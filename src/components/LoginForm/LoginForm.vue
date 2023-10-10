<template>
    <div class="flex flex-col gap-2 w-full border rounded-xl border-gray-700 backgroundBlur">
        <div class="text-center border-b border-gray-700 py-2">
            <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Account</h2>
        </div>
        <div class="text-center py-2">
            <p class="text-sm font-normal text-gray-500">Connect with your account.</p>
        </div>

        <div class="flex flex-col px-2">
            <div class="mb-6">
                <label for="username" class="block mb-2 text-sm font-medium text-white">Your username</label>
                <input type="username" id="username" class=" border text-sm rounded-lg block w-full p-2.5 bg-gray-700 border-gray-600 placeholder-gray-400 text-white dark" required>
            </div>
            <div class="mb-6">
                <label for="password" class="block mb-2 text-sm font-medium text-white">Your password</label>
                <input type="password" id="password" class=" border text-sm rounded-lg block w-full p-2.5 bg-gray-700 border-gray-600 placeholder-gray-400 text-white dark" required>
            </div>
            <button type="submit" class="text-white hover:bg-blue-800 focus:ring-4 focus:outline-none font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center bg-blue-600 hover: focus:ring-blue-800">Login</button>
        </div>
        <div class="flex text-center items-center justify-center py-2">
            <a href="#" class="inline-flex items-center text-xs font-normal text-gray-500 hover:underline">
                <svg class="w-3 h-3 mr-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7.529 7.988a2.502 2.502 0 0 1 5 .191A2.441 2.441 0 0 1 10 10.582V12m-.01 3.008H10M19 10a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
                </svg>
                Forget password ?
            </a>
        </div>
    </div>    
</template>

<script>

</script>