<template lang="">
  <div class="relative mx-24">
    <div class="flex justify-between p-4">
      <div class="flex items-center  gap-12">
        <h1> <router-link to="/">Lionel<span class="font-bold">GNONHOUE</span> </router-link></h1>
        <ul class='mr-12 flex items-center gap-4  '>
          <li >
          <router-link to="/" class="items-center flex space-x-2 hover:text-blue-600 duration-75 t" >
            <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 24 24"><path fill="black" d="M21 20a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9.49a1 1 0 0 1 .386-.79l8-6.223a1 1 0 0 1 1.228 0l8 6.223a1 1 0 0 1 .386.79z"/></svg>

            
            <p class=" hidden md:block"> Acueil</p>

          </router-link>

        </li>
          <li >
          <router-link to="/about" class="items-center flex space-x-1 hover:text-blue-600 duration-75 t">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 256 256"><g fill="black"><path d="M192 96a64 64 0 1 1-64-64a64 64 0 0 1 64 64" opacity="0.2"/><path d="M230.92 212c-15.23-26.33-38.7-45.21-66.09-54.16a72 72 0 1 0-73.66 0c-27.39 8.94-50.86 27.82-66.09 54.16a8 8 0 1 0 13.85 8c18.84-32.56 52.14-52 89.07-52s70.23 19.44 89.07 52a8 8 0 1 0 13.85-8M72 96a56 56 0 1 1 56 56a56.06 56.06 0 0 1-56-56"/></g></svg>

           
            <p class=" hidden md:block"> A propos</p>

          </router-link>

          </li>

          <li >
          <router-link to="/resumen" class="items-center flex space-x-1 hover:text-blue-600 duration-75 t">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 24 24"><g fill="none" stroke="black" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"><path d="M14 3v4a1 1 0 0 0 1 1h4"/><path d="M17 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7l5 5v11a2 2 0 0 1-2 2"/><path d="M11 12.5a1.5 1.5 0 0 0-3 0v3a1.5 1.5 0 0 0 3 0m2-4.5l1.5 6l1.5-6"/></g></svg>

            
            <p class=" hidden md:block">Resumen</p>

          </router-link>

          </li>

          <!-- <li >
          <router-link to="/portfolio" class="items-center flex space-x-1 hover:text-blue-600 duration-75 ">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 24 24"><path fill="black" d="M16 5V4a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v1a4 4 0 0 0-4 4v11a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V9a4 4 0 0 0-4-4m-6-1h4v1h-4zm2 5l2 2l-2 2l-2-2zm6 11H6v-4h2v2h1v-2h9zm0-5H6V9a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2z"/></svg>
            
            Portfolio

          </router-link>

          </li> -->
          <li >
            
          <router-link to="/contact" class="items-center flex space-x-1 hover:text-blue-600 duration-75 ">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 24 24"><path fill="black" d="M12 13.539q.633 0 1.066-.434t.434-1.066t-.434-1.067q-.433-.433-1.066-.433t-1.066.433t-.434 1.067t.434 1.066q.433.434 1.066.434m-3.5 3.384h7v-.152q0-.465-.248-.792t-.67-.52q-.591-.255-1.24-.396q-.65-.14-1.342-.14t-1.341.14t-1.242.396q-.42.193-.669.52q-.248.327-.248.792zM17.385 21H6.615q-.69 0-1.152-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h6.961L19 8.423v10.962q0 .69-.462 1.153T17.384 21m0-1q.231 0 .424-.192t.192-.424V8.85L13.15 4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192zM6 20V4z"/></svg>

            <p class=" hidden md:block">Contact</p>
          </router-link>

          </li>
         
        </ul>
      </div>
      <div>
        
        <a href=" mailto:lionelgnonhoue@gmail.com" class=" trans bg-black text-white p-1 md:p-2  rounded-md text-sm md:text-lg">Engagez-moi</a>
      </div>
    </div>
  </div>
</template>

<script setup>
import { RouterLink } from "vue-router";
</script>
