<template>
    <Drawer ref="drawer" gesturesEnabled="true">
        <StackLayout ~leftDrawer backgroundColor="#ffffff">
            <DrawerContent />
        </StackLayout>
        <Frame ~mainContent id="main">
            <Home />
        </Frame>
    </Drawer>
</template>

<script lang="ts">
  import { defineComponent } from 'nativescript-vue'
  import DrawerContent from './DrawerContent.vue'
  import Home from './Home.vue'

  export default defineComponent({
    components: {
      DrawerContent,
      Home
    }
  })
</script>
