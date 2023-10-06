<template>
    <div id="" class="flex flex-col items-start text-left">
        <div class="flex flex-row justify-center items-center gap-2">
            <svg class="w-4 h-4 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 9h2v5m-2 0h4M9.408 5.5h.01M19 10a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"/>
            </svg>
            <h2 class="text-lg font-semibold text-gray-900 dark:text-white">Server Info</h2>
        </div>
        <ul>
            <li v-for="(item, index) in serverDetails" :key="index" class="">
                <div>
                    <h3 class="pt-5 text-lg font-semibold text-gray-300 hover:text-gray-50">{{ item.titulo }}</h3>
                </div>
                <div class="w-auto text-gray-500 hover:text-gray-100 list-disc list-inside">
                    <p >{{ item.descricao }}</p>
                    <p v-if="item.descricao2" >{{ item.descricao2 }}</p>
                    <p v-if="item.descricao3" >{{ item.descricao3 }}</p>
                    <p v-if="item.descricao4" >{{ item.descricao4 }}</p>
                </div>
            </li>
        </ul>
    </div>
  </template>  
  <script>
  export default {
    data() {
      return {
        serverDetails: [{"titulo":"Episode: 3","descricao": "The server is based on Episode 3 of Shaiya."},
                        {"titulo":"Rates","descricao": "The server has a 5x EXP rate, but every day there is a x7 event if you don't have time to play."},
                        {"titulo":"Type of server","descricao": "The server is a PvE / PvP server, with a focus on grinding and farming."},
                        {"titulo":"Enchanting","descricao": "No enchant and no recreation."},
                        {"titulo":"Linking","descricao":"Original Linking rate - 100% link gm link"},
                        {"titulo":"Environment","descricao":"Original Maps and Monsters from Episode 3."},
                        {"titulo":"Kill Rate","descricao":"Normal Kill Rate: 1x, increased to x5 during events."},
                        {"titulo":"Stats", "descricao":"Original DEX formula from Episode 3. Original LUC formula increases critical attack."},
                        {"titulo":"Client Language","descricao":"English and Portuguese Language Client available."},
                        {"titulo":"Special Features","descricao":"No K.O NOSS (details not provided)."},
                        {"titulo":"Character Attributes","descricao":"100% Critical in PVE mode."},
                        {"titulo":"Shaiya Points","descricao":"Earn 2 SP per minute online. 1 hour of gameplay equals 120 SP.", "descricao2":"Vote to get 1050 Shaiya points, repeatable every 12 hours.", "descricao3":"Quests to get 600 Shaiya points, repeatable every 12 hours."},
                        {"titulo":"Economy","descricao":"Valorized gold (details not provided).", "descricao2":"Valorized quest items."},
                        {"titulo": "Security Measures", "descricao": "Anti skill cut.", "descricao2": "Anti-cheat system.", "descricao3": "Anti-dupe item system.", "descricao4": "Anti-DDoS protection."},
                        {"titulo": "Game Environment", "descricao": "Protected respawn zone."}]
      };
    }
  };
  </script>
  
  <style scoped>
  </style>
  