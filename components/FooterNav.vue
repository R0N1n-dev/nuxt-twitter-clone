<script setup>
const router = useRouter()
</script>

<template>
  <div class="_display:flex! _justify-content:space-around!">
    <IButton circle @click="router.push({ path: '/' })">
      <PhosphorIconHouseLine />
    </IButton>
    <IButton circle @click="router.push({ path: '/about' })">
      <PhosphorIconMagnifyingGlass />
    </IButton>
    <IButton circle>
      <PhosphorIconBell />
    </IButton>
    <IButton circle>
      <PhosphorIconEnvelopeSimple />
    </IButton>
  </div>
</template>

<style lang="scss" scoped>
div {
  button {
    margin-block: .2rem;
    border: none;
    background-color: #fff;
  }
}
</style>
