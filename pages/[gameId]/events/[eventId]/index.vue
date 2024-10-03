<template>
  <Breadcrumbs />
</template>

<script lang="ts" setup>
// const data = await $fetch('...');
// const dynamicPageName = `${data?.value?.pageName}`;
const dynamicPageName = 'This is the event name I want';
useBreadcrumbItems({
  overrides: [
    undefined,
    undefined,
    undefined,
    {
      to: '/cs/events/test',
      label: dynamicPageName
    }
  ]
});
</script>
