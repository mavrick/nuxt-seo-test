<template>
  <Breadcrumbs />
</template>

<script lang="ts" setup>
useBreadcrumbItems({
  overrides: [
    undefined,
    undefined,
    undefined,
    {
      to: '/cs/events/test',
      label: 'This is the event name I want'
    }
  ]
});
</script>
