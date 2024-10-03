<template>
  <div>{{ gameId }}</div>
</template>

<script lang="ts" setup>
const route = useRoute();
const { params = {} } = route;
const { gameId } = params;

definePageMeta({
  breadcrumb: {
    // icon: 'i-heroicons-home',
    label: 'Counter Strike',
  },
});
</script>
