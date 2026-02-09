<template>
    <TabView androidTabsPosition="bottom">
        <TabViewItem title="Home">
            <Frame id="items">
                <Items />
            </Frame>
        </TabViewItem>

        <TabViewItem title="Browse">
            <Frame id="browse">
                <Browse />
            </Frame>
        </TabViewItem>

        <TabViewItem title="Search">
            <Frame id="search">
                <Search />
            </Frame>
        </TabViewItem>
    </TabView>
</template>

<script lang="ts">
  import { defineComponent } from 'nativescript-vue'
  import Items from './Items.vue'
  import Browse from './Browse.vue'
  import Search from './Search.vue'

  export default defineComponent({
    components: {
      Items,
      Browse,
      Search
    }
  })
</script>
