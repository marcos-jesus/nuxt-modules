<script>
  export default {
    setup() {
      onMounted(() => {
        const layout = definePageMeta({
          login: 'auth'
        })

        return layout
      })

    }
  }

</script>
<template>
  <NuxtLayout :name="layout">
    <div class="mt-5 mb-5">
      Login
    </div>
  </NuxtLayout>
</template>
