<script setup>
  import ProfileCompo from '@/components/ProfileCompo.vue'


</script>



<template>
  <div class="mt-[4rem]">
   
   <div class="mx-24 " >
    <div class="flex gap-10">
     <div class="hidden md:block">
      <ProfileCompo />

    </div>
    <div >
     <div>
      <div class="mb-3">
          <p class="italic"> A <span class="text-[#4B0082] font-bold">Propos</span> </p>
          <div class="bg-[#dddd] h-0.5"></div>
         </div>
        <div class="max-w-[74%] space-y-3 mb-6">
          <p class="text-sm md:text-xl">
            Avec mon expertise avérée en rédaction web, je produis des contenus de qualité supérieure qui captivent votre audience et stimulent vos objectifs marketing. Ma maîtrise irréprochable des règles de syntaxe, de grammaire, d'orthographe et de conjugaison garantit des textes impeccables et percutants.
          </p>
          <p class="">
            Mon approche collaborative et ma communication claire garantissent une expérience de travail fluide et agréable.
          </p>
        </div>
     </div>

      <div class="">
        <div class="grid grid-cols-1 md:grid-cols-2 items-center" >
          <div class="mb-5">
            <p>AGE</p>
            <p class="font-bold">23ans</p>
          </div>

          <div class="mb-5">
            <p>Loclisatons</p>
            <p class="font-bold">Abomey-calavi</p>
          </div>

          <div class="mb-5">
            <p>Numero</p>
            <a href="tel:+22990506744 " class="font-bold">+22990506744</a>

          </div>

          <div class="mb-5">
            <p>Email</p>
            <p>Abomey-calavi</p>
          </div>

          <router-link to="" class="bg-[#4B0082] p-4 text-[#fff] rounded-md max-w-[50%] "> Telecharger mon CV</router-link>


        </div>
        <div class="my-12">
         <div class="mb-3">
          <p class="italic">Mes  <span class="text-[#4B0082] font-bold">Services</span> </p>
          <div class="bg-[#dddd] h-0.5"></div>
         </div>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-3">
          
            <div class="">
              <div class="border p-3 flex gap-2">
                
                <div class="">
                  <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 512 512"><path fill="#d19b61" d="M198.373 319.086v167.272c0 11.4 27.197 20.642 60.746 20.642c33.549 0 60.746-9.242 60.746-20.642V319.086z"/><path fill="#81929b" d="M500.242 181.857c0-61.435-49.803-111.238-111.238-111.238H124.036l111.238 313.834h257.768a7.2 7.2 0 0 0 7.2-7.2V189.057c0-.497-.05-.982-.146-1.451c.096-1.904.146-3.821.146-5.749"/><path fill="#bcc8cc" d="M124.036 70.619c-61.435 0-111.238 49.803-111.238 111.238v195.396a7.2 7.2 0 0 0 7.2 7.2h208.076a7.2 7.2 0 0 0 7.2-7.2V181.857c0-61.435-49.803-111.238-111.238-111.238"/><path fill="#ff473e" d="M398.984 5.525h-58.093c-18.729 0-34.461 12.829-38.891 30.178a23.411 23.411 0 0 0-2.213 9.959v162.843c0 12.984 10.525 23.509 23.509 23.509s23.509-10.525 23.509-23.509V85.8h52.179c22.167 0 40.138-17.97 40.138-40.137S421.151 5.525 398.984 5.525"/></svg>
                </div>
                <div >
                  <p class="font-bold">Closing</p>
                    <p>
                      Je suis un closer expérimenté et j'ai aidé de nombreuses entreprises à atteindre leurs objectifs de vente. Je suis convaincu que je peux vous aider à faire de même.
                    </p>
                </div>
              </div>
            </div>
          

            <div class="">
              <div class="border p-3 flex gap-2">
                
                <div class="">
                  <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 512 512"><path fill="#d19b61" d="M198.373 319.086v167.272c0 11.4 27.197 20.642 60.746 20.642c33.549 0 60.746-9.242 60.746-20.642V319.086z"/><path fill="#81929b" d="M500.242 181.857c0-61.435-49.803-111.238-111.238-111.238H124.036l111.238 313.834h257.768a7.2 7.2 0 0 0 7.2-7.2V189.057c0-.497-.05-.982-.146-1.451c.096-1.904.146-3.821.146-5.749"/><path fill="#bcc8cc" d="M124.036 70.619c-61.435 0-111.238 49.803-111.238 111.238v195.396a7.2 7.2 0 0 0 7.2 7.2h208.076a7.2 7.2 0 0 0 7.2-7.2V181.857c0-61.435-49.803-111.238-111.238-111.238"/><path fill="#ff473e" d="M398.984 5.525h-58.093c-18.729 0-34.461 12.829-38.891 30.178a23.411 23.411 0 0 0-2.213 9.959v162.843c0 12.984 10.525 23.509 23.509 23.509s23.509-10.525 23.509-23.509V85.8h52.179c22.167 0 40.138-17.97 40.138-40.137S421.151 5.525 398.984 5.525"/></svg>
                </div>
                <div >
                  <p class="font-bold">Closing</p>
                    <p>
                      Je suis un closer expérimenté et j'ai aidé de nombreuses entreprises à atteindre leurs objectifs de vente. Je suis convaincu que je peux vous aider à faire de même.
                    </p>
                </div>
              </div>
            </div>

            <div class="">
              <div class="border p-3 flex gap-2">
                
                <div class="">
                  <svg xmlns="http://www.w3.org/2000/svg" width="1.5em" height="1.5em" viewBox="0 0 512 512"><path fill="#d19b61" d="M198.373 319.086v167.272c0 11.4 27.197 20.642 60.746 20.642c33.549 0 60.746-9.242 60.746-20.642V319.086z"/><path fill="#81929b" d="M500.242 181.857c0-61.435-49.803-111.238-111.238-111.238H124.036l111.238 313.834h257.768a7.2 7.2 0 0 0 7.2-7.2V189.057c0-.497-.05-.982-.146-1.451c.096-1.904.146-3.821.146-5.749"/><path fill="#bcc8cc" d="M124.036 70.619c-61.435 0-111.238 49.803-111.238 111.238v195.396a7.2 7.2 0 0 0 7.2 7.2h208.076a7.2 7.2 0 0 0 7.2-7.2V181.857c0-61.435-49.803-111.238-111.238-111.238"/><path fill="#ff473e" d="M398.984 5.525h-58.093c-18.729 0-34.461 12.829-38.891 30.178a23.411 23.411 0 0 0-2.213 9.959v162.843c0 12.984 10.525 23.509 23.509 23.509s23.509-10.525 23.509-23.509V85.8h52.179c22.167 0 40.138-17.97 40.138-40.137S421.151 5.525 398.984 5.525"/></svg>
                </div>
                <div >
                  <p class="font-bold">Closing</p>
                    <p>
                      Je suis un closer expérimenté et j'ai aidé de nombreuses entreprises à atteindre leurs objectifs de vente. Je suis convaincu que je peux vous aider à faire de même.
                    </p>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
    </div>
   </div>
  </div>
</template>

<!-- <style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style> -->
