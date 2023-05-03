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
    <h2 class="text-lg font-bold">Produtos</h2>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ab totam asperiores quod repellat dolorum tempora, aut fugiat dolorem, delectus molestias explicabo doloribus! Et, inventore nesciunt id mollitia iure dolore non.</p>
  </div>
</template>