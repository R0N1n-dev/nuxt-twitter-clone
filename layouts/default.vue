<template>
  <ILayout vertical>
    <ILayoutAside class="_sm:visible!">
      <SidebarIcons />
    </ILayoutAside>
    <ILayout>
      <ILayoutHeader> Home </ILayoutHeader>
      <ILayoutContent>
        <slot />
      </ILayoutContent>
      <ILayoutFooter class="_sm:hidden _position:fixed-bottom! _border-top! _padding:0.5">
        <FooterNav />
      </ILayoutFooter>
    </ILayout>
  </ILayout>
</template>

