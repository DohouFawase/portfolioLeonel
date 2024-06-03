<script setup>
import { RouterView } from "vue-router";
import NavBarView from "../components/navigation/NavBarView.vue";
import { onMounted, ref } from 'vue';
import "animate.css";

</script>

<template>
  <div>
    <div>
      <NavBarView />
    </div>
    <!-- <div class=''> -->
    <router-view v-slot="{ Component, route }">
      <transition
       
        leave-active-class="animate__animated animate__bounceOutRight"
        mode="out-in"
       
      >
        <component :is="Component" :key="route.path" />
      </transition>
      <slot />
    </router-view>
    <!-- </div> -->
  </div>
</template>
