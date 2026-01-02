<template>
  <ul tabindex="-1" class="menu menu-sm dropdown-content rounded-box z-1 mt-3 w-52 p-2 shadow bg-black text-white rounded border-accent card-border font-bold">
    <li><a @click="NavigationTo('/home')">Home</a></li>
    <li><a @click="NavigationTo('/projects')">Projetos</a></li>
    <li><a @click="NavigationTo('/contact')">Contato</a></li>
  </ul>
</template>
<script setup>
import { useRouter } from 'vue-router';

const router = useRouter()

async function NavigationTo(rota){
  if(rota == "/home" || rota == '/home') {
    router.push('/')
    return
  }
  router.push(rota)
}
</script>
