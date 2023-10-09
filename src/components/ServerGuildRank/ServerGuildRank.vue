<template>
    <div id="" class="flex flex-col items-start text-left">
        <div class="flex flex-col gap-2 w-full border rounded-xl border-gray-700 backgroundBlur">
            <div class="text-center border-b border-gray-700 py-2">
                <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-white">Guild Rank.</h2>
            </div>
            <div class="text-center py-2">
                <p class="text-sm font-normal text-gray-500 dark:text-gray-400">Top 10 Guilds</p>
            </div>
            
            <div class="relative overflow-x-auto shadow-md;;;;">
                <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
                    <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                        <tr>
                            <th scope="col" class="px-6 py-3">
                                Name
                            </th>
                            <th scope="col" class="px-6 py-3">
                                Leader
                            </th>
                            <th scope="col" class="px-6 py-3">
                                Points
                            </th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr v-for="(item, index) in guilds" :key="index"   class="bg-white dark:bg-gray-800 hover:bg-gray-50 dark:hover:bg-gray-600">
                            <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                {{ item.nome }}
                            </th>
                            <td class="px-6 py-4">
                                {{ item.lider }}
                            </td>
                            <td class="px-6 py-4">
                                {{ item.pontos }}
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</template>  
  <script>
  export default {
    data() {
      return {
        guilds: [{"nome": "Orion", "lider": "Viserion", "pontos": "34189"},
                        {"nome": "Orion", "lider": "Viserion", "pontos": "34189"},
                        {"nome": "Orion", "lider": "Viserion", "pontos": "34189"},
                        {"nome": "Orion", "lider": "Viserion", "pontos": "34189"},
                        {"nome": "Orion", "lider": "Viserion", "pontos": "34189"},
                        {"nome": "Orion", "lider": "Viserion", "pontos": "34189"}
                ]  
      };
    }
  };
  </script>
  
  <style scoped>
  </style>
  