<template>
  <div class="bg-gray-300">
    <div class="container mx-auto flex items-center font-bold space-x-4 h-10">
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
    <h1 class="text-lg font-bold">A empresa</h1> 
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem praesentium totam, a quibusdam maxime similique blanditiis ipsa. Sunt amet similique explicabo exercitationem. Aliquam facilis odio placeat natus possimus illum dolores.</p>
  </div>

</template>