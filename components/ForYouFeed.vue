<script setup></script>

<template>
  <IMedia>
    <template #image>
      <img class="_border-radius:50%!" src="https://placehold.co/40x40" alt="Media Image" />
    </template>
    <h6 class="_margin:0">Media Title</h6>
    <p class="_margin:0">
      For you
    </p>
    <div class="_margin-top:2 _display:flex! _justify-content:space-between! icons">

      <PhosphorIconChatCircle class="chat" />


      <PhosphorIconArrowsClockwise />


      <PhosphorIconHeart />


      <PhosphorIconChartBar />

      <PhosphorIconExport />

    </div>
  </IMedia>
</template>
<style lang="scss" scoped>
div svg:first-child {
  margin-right: 2rem;
}

div svg:not(:first-child) {
  margin-block: .2rem;
  margin-inline: 2.8rem;
}

svg {
  border: none;
  background-color: #fff;
}

@media screen and (max-width:575px) {
  div svg:first-child {
    margin-right: 1.2rem;
  }

  div svg:not(:first-child) {
    margin-inline: 2.3rem;
  }
}

.chat:hover {
  background-color: lightblue;
  color: rgb(35, 125, 155);
  height: 15px;
  width: 15px;
  border-radius: 50%;
}
</style>