<template>
    <div id="" class="flex flex-col items-start text-left">
        <div class="flex flex-col w-full border rounded-xl border-gray-700 backgroundBlur">
            <div class="text-center border-b border-gray-700 py-2">
                <h2 class="text-sm md:text-base lg:text-md font-semibold tracking-tight leading-none text-gray-200">PvP Rank</h2>
            </div>          
            <div class="relative overflow-x-auto shadow-md;;;;">
                <table class="w-full text-sm text-left text-gray-400">
                    <thead class="text-xs uppercase bg-gray-700 text-gray-400">
                        <tr>
                            <th scope="col" class="px-6 py-3">
                                Name
                            </th>
                            <th scope="col" class="px-6 py-3">
                                Level
                            </th>

                            <th scope="col" class="px-6 py-3">
                                Kills
                            </th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr v-for="(item, index) in pvp" :key="index"   class=" bg-gray-800 hover hover:bg-gray-600 text-gray-400">
                            <th scope="row" class="px-6 py-4 font-medium whitespace-nowrap text-gray-400">
                                {{ item.nome }}
                            </th>
                            <td class="px-6 py-4">
                                {{ item.level }}
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
        pvp: [{"nome": "Death_Only","level": "60","guild": "Sem Futuro","pontos": "1941"},
                {"nome": "Morted", "level": "15","guild": "", "pontos": "1941"},
                {"nome": "Death", "level": "30","guild": "", "pontos": "1941"},
                {"nome": "Matador", "level": "53","guild": "", "pontos": "1941"},
                {"nome": "LOBINHO", "level": "60","guild": "", "pontos": "1715"},
                {"nome": "[GS]Abud", "level": "60","guild": "REBIRTH", "pontos": "1715"},
                {"nome": "SHOCKER", "level": "30","guild": "REBIRTH", "pontos": "1715"},
                {"nome": "-MC-", "level": "30","guild": "FuriaLatina", "pontos": "1489"},
                {"nome": ".MC.", "level": "15","guild": "FuriaLatina", "pontos": "1489"},
                {"nome": "MC", "level": "60","guild": "", "pontos": "1489"},
                {"nome": "GBR", "level": "60","guild": "FuriaLatina", "pontos": "1489"},
                {"nome": "Bazuca", "level": "35","guild": "", "pontos": "1489"},
                {"nome": "..Lisana..", "level": "30","guild": "", "pontos": "1485"},
                {"nome": "LEO", "level": "60","guild": "Sem Futuro", "pontos": "1485"},
                {"nome": "LEO", "level": "15","guild": "", "pontos": "1485"}]	   
      };
    }
  };
  </script>
  
  <style scoped>
  </style>
  