<template lang="">
    <div >
        <div class=" bg-yellow-400  max-w-[20rem]">
          <img :src="Image" class="pl-4 pt-12">
          <div class="my-4">
            <div class="px-8 py-4">
              <p class='font-bold '>Lionel</p>
              <p >Web Redacteur | Abomey-calavi</p>
            </div>
            <div class="hidden md:flex items-center gap-4 px-8 py-4">
              <div class="h-10 bg-black w-0.5 "></div>
              <div class=" text-xs flex flex-col  ">
                <a href="tel:+22990506744 " class="font-bold">+22990506744</a>
                <a href="mailto:lionelgnonhoue@gmail.com" class="font-bold">lionelgnonhoue@gmail.com</a>
          
              </div>
            </div>
          </div>

          <div class=" px-8 ">
            <div class="flex gap-3 items-center py-4">
              <a href="https://www.facebook.com/profile.php?id=100091880357434" class="icone">
                <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 16 16"><path fill="black" d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131c.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"/></svg>
              </a>
              <a href="" class="icone">
                <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 16 16"><path fill="black" d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334q.002-.211-.006-.422A6.7 6.7 0 0 0 16 3.542a6.7 6.7 0 0 1-1.889.518a3.3 3.3 0 0 0 1.447-1.817a6.5 6.5 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.32 9.32 0 0 1-6.767-3.429a3.29 3.29 0 0 0 1.018 4.382A3.3 3.3 0 0 1 .64 6.575v.045a3.29 3.29 0 0 0 2.632 3.218a3.2 3.2 0 0 1-.865.115a3 3 0 0 1-.614-.057a3.28 3.28 0 0 0 3.067 2.277A6.6 6.6 0 0 1 .78 13.58a6 6 0 0 1-.78-.045A9.34 9.34 0 0 0 5.026 15"/></svg>
              </a>
              <a href="" class="icone">
                <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 24 24"><path fill="black" d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037c-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85c3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.06 2.06 0 0 1-2.063-2.065a2.064 2.064 0 1 1 2.063 2.065m1.782 13.019H3.555V9h3.564zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0z"/></svg>
              </a>
            </div>
          </div>
        </div> 
    </div>
</template>


<script setup>
  import Image from '@/assets/imgs/ro.jpg'
import 'animate.css';
  
</script>