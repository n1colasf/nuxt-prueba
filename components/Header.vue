<template>
  <header class="bg-emerald-700">
    <div class="flex flex-row">
      <h3 class="text-3xl font-bold m-1 mr-4">HEADER</h3>
      <NuxtLink class="text-lg nav-link mt-2 mx-2 m-1 text-gray-100" to="/"
        >home</NuxtLink
      >
      <NuxtLink class="text-lg nav-link mx-2 mt-2 m-1 text-gray-100" to="/about"
        >about</NuxtLink
      >
      <NuxtLink class="text-lg nav-link mx-2 mt-2 m-1 text-gray-100" to="/tests"
        >tests</NuxtLink
      >
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped></style>
