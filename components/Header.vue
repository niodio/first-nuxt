<template>
  <div class="bg-gray-100">
    <div
      class="container mx-auto space-x-4 flex justify-center items-center border"
    >
      <NuxtLink to="/a-empresa"> A Empresa </NuxtLink>
      <NuxtLink to="/servicos"> Serviços </NuxtLink>
      <NuxtLink to="/produtos"> Produtos </NuxtLink>
      <NuxtLink to="/produtos/prod"> PROD </NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style></style>
