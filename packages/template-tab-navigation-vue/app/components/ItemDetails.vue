<template>
    <Page>
        <ActionBar>
            <NavigationButton @tap="$navigateBack()" android.systemIcon="ic_menu_back"/>
            <Label :text="item.name"/>
        </ActionBar>

        <GridLayout>
            <Label class="m-2 text-lg" :text="item.description" verticalAlignment="top"/>
        </GridLayout>
    </Page>
</template>

<script lang="ts">
  import { defineComponent } from 'nativescript-vue'

  export default defineComponent({
    props: ['item']
  })
</script>
