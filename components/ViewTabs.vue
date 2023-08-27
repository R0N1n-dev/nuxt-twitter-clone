<script setup>
const active = ref('tab-1')
</script>

<template>
  <ITabs v-model="active" stretch>
    <template #header>
      <ITabTitle for="tab-1"> For you </ITabTitle>
      <ITabTitle for="tab-2"> Following </ITabTitle>
    </template>

    <ITab name="tab-1">
      <ForYouFeed />
    </ITab>
    <ITab name="tab-2">
      <FollowingFeed />
    </ITab>
  </ITabs>
</template>

<style lang="scss" scoped>
.tabs {
  --tabs--tab--border-style: none;
  --tabs--header--border-style: none;
  --tabs--title--border-style: none;
}
</style>