<script setup></script>

<template>
  <div class="_display:flex! _justify-content:space-around!">
    <IButton circle to="/">
      <PhosphorIconHouseLine />
    </IButton>
    <IButton circle to="/about">
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
