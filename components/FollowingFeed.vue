<script setup></script>

<template>
  <IMedia>
    <template #image>
      <img class="_border-radius:50%!" src="https://placehold.co/40x40" alt="Media Image" />
    </template>
    <h3 class="_margin:0">Media Title</h3>
    <p class="_margin:0">
      Following
    </p>
    <div>
      <IButton circle>
        <PhosphorIconChatCircle />
      </IButton>
      <IButton circle>
        <PhosphorIconArrowsClockwise />
      </IButton>
      <IButton circle>
        <PhosphorIconHeart />
      </IButton>
      <IButton circle>
        <PhosphorIconChartBar />
      </IButton>
      <IButton circle>
        <PhosphorIconExport />
      </IButton>
    </div>
  </IMedia>
</template>
<style lang="scss" scoped>
button {
  margin-block: .2rem;
  margin-inline: 1rem;
  border: none;
  background-color: #fff;
}
</style>