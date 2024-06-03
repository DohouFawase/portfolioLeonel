<script setup>
  import ProfileCompo from '@/components/ProfileCompo.vue'
  import {RouterLink}  from 'vue-router'
  import 'gsap';

</script>

<template>
  <main class="mt-[4rem]">
    <div class="mx-24 grid grid-cols-1 md:grid-cols-2  gap-14   ">
      <div class="">
        <ProfileCompo />

      </div>
        <div class="my-6">
          <div class="relative">
            <p class="">Je suis <span class="font-bold text-xl">GNONHOUE  R.G</span></p>
            <p class="red font-bold ">Redacteur Web</p>
          </div>
        <p class="min-w-[50%] my-6"> Rédacteur web freelance expérimenté avec une  bonne maîtrise des règles  de 
          syntaxe, de grammaire, d'orthographe et  de conjugaison .Capacité de managériales et esprit très créatif
          pouvant travailler sur 
          des project de toute sorte
        </p>
        <div class="flex items-center gap-6">
          <router-link to="/contact" class="bg-[#4B0082] p-4 text-[#fff] rounded-md "> Contactez-moi</router-link>
          <div class="flex ">
            <router-link to="/about" class="flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24"><g fill="black"><path d="m14.829 12.026l1.414 1.414L12 17.683L7.757 13.44l1.415-1.414L11 13.854V6.317h2v7.537z"/><path fill-rule="evenodd" d="M19.778 19.778c-4.296 4.296-11.26 4.296-15.556 0c-4.296-4.296-4.296-11.26 0-15.556c4.296-4.296 11.26-4.296 15.556 0c4.296 4.296 4.296 11.26 0 15.556m-1.414-1.414A9 9 0 1 1 5.636 5.636a9 9 0 0 1 12.728 12.728" clip-rule="evenodd"/></g></svg>
              A propos
            </router-link>

          </div>
        </div>
      </div>
    </div>
     

      
  </main>
</template>
