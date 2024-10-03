<template>
  <pre>{{ breadcrumbs }}</pre>
</template>

<script lang="ts" setup>
const breadcrumbs = useBreadcrumbItems({ schemaOrg: true });
</script>
