<template>    
    <div class="flex flex-col w-full border rounded-xl border-gray-700 backgroundBlur">
        <div class="text-center border-b border-gray-700 py-2">
            <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Server Status</h2>
        </div>
        <table class="flex flex-row w-full text-sm text-gray-400">
            <thead class="flex flex-col w-1/4 text-xs uppercase bg-gray-700 text-gray-400">
                <tr class="flex flex-col">
                    <th scope="col" class="py-3">
                        status
                    </th>
                    <th scope="col" class="py-3">
                        drop
                    </th>
                    <th scope="col" class="py-3">
                        exp
                    </th>
                    <th scope="col" class="py-3">
                        kill
                    </th>
                    <th scope="col" class="py-3">
                        grb
                    </th>
                </tr>
            </thead>
            <tbody class="flex flex-col w-3/5 text-left text-xs uppercase"> 
                <tr v-for="(item, index) in status" :key="index"  class="flex flex-col">
                    <th class="px-3 py-3">
                        {{ item.status }}
                    </th>
                    <td class="px-3 py-3">
                        {{ item.drop }}
                    </td>
                    <td class="px-3 py-3">
                        {{ item.exp }}
                    </td>
                    <td class="px-3 py-3">
                        {{ item.kill }}
                    </td>
                    <td class="px-3 py-3">
                        {{ item.grb }}
                    </td>
                </tr>
            </tbody>
        </table> 
    </div>
</template>

<script >
export default {
    data() {
        return {
            status: [
                        {
                            "status": "Maintenance", 
                            "version": "Episode 3", 
                            "drop": "Original", 
                            "exp": "exp 10x", 
                            "kill": "x1 (x5 events)", 
                            "grb": "Sunday 21:00 UTC -3"
                        }
                    ]
            
        }
    }
}

</script>