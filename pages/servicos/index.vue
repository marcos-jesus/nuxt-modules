<template>
  <div class="bg-gray-300">
    <div class="container mx-auto flex items-center space-x-4 h-10 font-bold">
      <nuxt-link 
        to="/" 
        class="hover:text-green-500"
      >
        Inicio
      </nuxt-link>

      <nuxt-link
        :to="{ name: 'empresa' }" 
        class="hover:text-green-500"
      >
        Empresa
      </nuxt-link>

      <nuxt-link 
        :to="{ name: 'servicos' }" 
        class="hover:text-green-500"
      >
        Serviços
      </nuxt-link>
      
      <nuxt-link 
        :to="{ name: 'produtos' }" 
        class="hover:text-green-500"
      >
        Produtos
      </nuxt-link>
    </div>
  </div>

  <div class="container mx-auto">
      <h1 class="text-lg font-bold">Serviços</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minima obcaecati iste quae quo, vero excepturi voluptates deleniti culpa voluptas dolorem harum perspiciatis nemo incidunt impedit tempore, neque error, corrupti laboriosam.</p>
    </div>
</template>