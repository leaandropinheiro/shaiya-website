<template>
    <div id="" class="flex flex-col items-start text-left">
        <div class="flex flex-col w-full border rounded-xl border-gray-700 backgroundBlur">
            <div class="text-center border-b border-gray-700 py-2">
                <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-gray-200">Guild Rank.</h2>
            </div>            
            <div class="relative overflow-x-auto shadow-md;;;;">
                <table class="w-full text-sm text-left text-gray-400">
                    <thead class="text-xs uppercase bg-gray-700 text-gray-400">
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
                        <tr v-for="(item, index) in guilds" :key="index"  class=" bg-gray-800 hover:bg-gray-600 text-gray-400">
                            <th scope="row" class="px-6 py-4 font-medium whitespace-nowrap text-gray-400">
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
  