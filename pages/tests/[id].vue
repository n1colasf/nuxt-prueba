<template>
  <h2 class="text-center text-9xl font-bold mt-20 mb-8">TEST # {{ id }}</h2>
</template>

<script setup>
const { id } = useRoute().params;

definePageMeta(
    {
        validate: async (route) => {
            const nuxtApp = useNuxtApp()
            return route.params.id === '1' || route.params.id === '2' || route.params.id === '3' || route.params.id === 'test'
        }
    }
)




</script>

<style scoped></style>
