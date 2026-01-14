<template>
  <div class="navbar bg-secondary text-primary-content px-4">
    <div class="flex-1 flex items-center gap-2">
      <div class="dropdown">

        <div tabindex="0" role="button" class="btn btn-ghost btn-circle">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h7" />
          </svg>
        </div>

        <NavPages />
      </div>

      <button class="btn btn-ghost text-sm md:text-xl text-white">
        Portfólio de Anderson Patricio
      </button>
    </div>

    <div class="hidden md:flex flex-1 flex-col items-center justify-center">
      <div class="flex gap-2 items-center">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="Icone de C#">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Icone de Java">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="Icone de Spring">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="Icone de Javascript">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="Icone de React">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="Icone de VueJS">
        <img height="16" width="24" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="Icone de Flutter">
      </div>

      <p class="text-sm text-center">
        Desenvolvedor FullStack
      </p>
    </div>

    <div class="flex-1 flex justify-end">
      <label class="flex cursor-pointer items-center gap-1">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
          fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <circle cx="12" cy="12" r="5" />
          <path d="M12 1v2M12 21v2M4.2 4.2l1.4 1.4M18.4 18.4l1.4 1.4M1 12h2M21 12h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4" />
        </svg>

        <input type="checkbox" value="black"
          class="toggle theme-controller bg-gray-700 rounded" />

        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24"
          fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M21 12.79A9 9 0 1 1 11.21 3
            7 7 0 0 0 21 12.79z" />
        </svg>
      </label>
    </div>
  </div>
</template>
