<script lang="ts" setup>
const { data: api } = await useFetch("/api/clients");
</script>

<template>
  <div>
    <h1 class="text-persian-blue-500">
      {{ api }}
      <span class="text-gray-100" />
    </h1>
  </div>
</template>
