<script setup>
//imports here
import Navbar from './components/Navbar/Navbar.vue'
import Sidebar from './components/Sidebar/Sidebar.vue';
import DarkModeButton from './components/DarkModeButton/DarkModeButton.vue';

</script>

<template>
  <div>
    <Navbar />
  </div>

  <section class="flex items-center justify-center bg-gray-800 bg-blend-multiply">
    <div class="">
      <div class="">
        <img src="https://cdn.discordapp.com/attachments/1077021017744085082/1159906955872186448/image.png?ex=6532ba88&is=65204588&hm=6d9cec55a4ed3f0e07a5fbf96e576098423034012e2b378fb8d0a0fdce8efa3f&" alt="" id="ainda" class="z-0 absolute shadow-[inset_10_10px_10px_rgba(127, 17, 224, 1)]">
      </div>
      <div class="lg:py-16 py-8 md:py-8 mx-auto max-w-screen-xl text-center z-10 relative">
        <a href="#" class="flag inline-flex justify-between items-center mb-4 py-1 px-1 pr-4 text-sm rounded-full text-blue-300">
              <span class="text-xs bg-blue-600 rounded-full text-white px-4 py-1.5">Get Started</span> <span class="text-sm font-medium ml-2">Play for Free!</span> 
              <svg class="w-2.5 h-2.5 ml-2" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
              </svg>
          </a>
          <h1 class="text-4xl mb-4 font-extrabold tracking-tight leading-none md:text-5xl lg:text-6xl text-white">Lorem, ipsum</h1>
          <p class="text-lg font-normal lg:text-xl sm:px-16 lg:px-48 text-gray-200">Lorem ipsum dolor sit amet consectetur adipisicing elit. s iure! Labore quod recusandae natus in mollitia consectetur laudantium officiis. Eius neque recusandae aperiam.</p>
      </div>    
    </div>
  </section>

  <main class="flex items-center justify-center bg-gray-800 bg-blend-multiply">
    <div class="px-4 w-screen max-w-screen-xl text-center lg:py-16 z-10 relative">
        <Sidebar />
    </div>      
  </main>
</template>

<style scoped>

</style>
