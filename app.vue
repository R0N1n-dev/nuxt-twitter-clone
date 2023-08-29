<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style>
:root {
  --layout-aside--width: 4rem;
}

html {
  scroll-behavior: smooth;
}

.page-enter-active,
.page-leave-active {
  transition: all 0.08s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
}
</style>
