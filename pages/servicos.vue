<template>
  <div>
    <h1 class="text-lg font-bold">Serviços</h1>
    <NuxtLink to="/servicos/desenvolvimento-de-sites">
      Desenvolvimento de Sites
    </NuxtLink>
    <NuxtLink to="/servicos/marketing-digital"> Marketing Digital </NuxtLink>
    <br />

    <NuxtChild />
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
};
</script>
