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
      to: '/test/events/test-2',
      label: 'This is the event name I want'
    }
  ]
});
</script>
