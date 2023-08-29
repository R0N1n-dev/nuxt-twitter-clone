<script setup>
const search = ref('')
</script>

<template>
  <div>
    <IInput v-model="search" placeholder="Search">
      <template #prefix>
        <PhosphorIconMagnifyingGlass />
      </template>
    </IInput>
  </div>
</template>

<style scoped></style>
