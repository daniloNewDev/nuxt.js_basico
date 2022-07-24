<template>
    <div>
      <h1 class="text-lg font-bold">Produtos</h1>
      <NuxtLink to="/produtos/produto-a">
        Produto A
      </NuxtLink>
      <NuxtLink to="/produtos/produto-b">
        Produto B
      </NuxtLink>
      <br/>

      <NuxtChild />

    </div>
</template>

<script>
  export default {
    name: '',
    data() {
      return {

      }
    }
  }
</script>