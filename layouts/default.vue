<template>
  <ILayout vertical>
    <ILayoutAside>
      <SidebarIcons />
    </ILayoutAside>
    <ILayout>
      <ILayoutHeader> Home </ILayoutHeader>
      <ILayoutContent>
        <slot />
      </ILayoutContent>
      <ILayoutFooter> Footer </ILayoutFooter>
    </ILayout>
  </ILayout>
</template>

