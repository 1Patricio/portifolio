<template>
  <div class="hero bg-base-200 max-h-screen">
    <div class="hero-content flex-col lg:flex-row-reverse">
      <img
        src="../assets/images/projects.webp"
        class="w-sm rounded-lg md:shadow-2xl sm:ml-16"
        alt="Foto de mesa de escritório"
      />
      <div>
        <h1 class="text-3xl font-bold sm:text-5xl">Meus projetos!</h1>
        <p class="py-6">
          Vejas alguns projetos que desenvolvi ao longo da minha jornada, explorando ideias, desafios e soluções através
          do código.
        </p>
        <button
          class="btn bg-gray-700 text-white border-gray-700 mx-1"
          @click="NavigationTo('/projects')"
        >
         <img src="../assets/images/projetos-icon.webp" alt="Icone Projetos" width="20" height="20">
          Projetos
        </button>
      </div>
    </div>
  </div>
</template>
<script setup>
import { useRouter } from 'vue-router';

const router = useRouter()

async function NavigationTo(rota){
  router.push(rota)
}
</script>
