<script setup></script>

<template>
  <IMedia>
    <template #image>
      <img class="_border-radius:50%!" src="https://placehold.co/40x40" alt="Media Image" />
    </template>
    <h3 class="_margin:0">Media Title</h3>
    <p class="_margin:0">
      For you
    </p>
    <div>

      <PhosphorIconChatCircle />


      <PhosphorIconArrowsClockwise />


      <PhosphorIconHeart />


      <PhosphorIconChartBar />

      <PhosphorIconExport />

    </div>
  </IMedia>
</template>
<style lang="scss" scoped>
svg {
  margin-block: .2rem;
  margin-inline: 1rem;
  border: none;
  background-color: #fff;
}
</style>