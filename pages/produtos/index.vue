<script>
export default {
  setup() {
    async function asyncData() {
      await new Promise((resolve) => {
      setTimeout(() => {
        resolve()
        console.log('promisse resolved')
      }, 3000)
    })

    }
    const products =  [
      { name: 'product-a'},
      { name: 'product-b'}
    ]

    return {
      asyncData,
      products
    }
  }
}

</script>
<template>
  <h2 class="text-lg font-bold mt-5 mb-5">Produtos</h2>
  <div class="space-x-4 mb-4 font-bold">
    <nuxt-link 
      to="/produtos/produto-a" 
      class="hover:text-green-500"
    >
      Produto A
    </nuxt-link>

    <nuxt-link 
      to="/produtos/produto-b" 
      class="hover:text-green-500"
    >
      Produto B
    </nuxt-link>
  </div>
  <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ab totam asperiores quod repellat dolorum tempora, aut fugiat dolorem, delectus molestias explicabo doloribus! Et, inventore nesciunt id mollitia iure dolore non.</p>

  <h3> {{ products }} </h3>
</template>