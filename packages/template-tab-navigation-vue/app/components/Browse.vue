<template>
    <Page>
        <ActionBar>
            <Label text="Browse"/>
        </ActionBar>

        <GridLayout>
            <Label class="far text-7xl text-gray-400 text-center" style="vertical-align: top; margin-top: 20%" :text="'\uf1ea'"/>
            <Label class="text-xl text-gray-400 text-center align-middle" text="Browse page content goes here"/>
        </GridLayout>
    </Page>
</template>

<script lang="ts">
  import { defineComponent } from 'nativescript-vue'

  export default defineComponent({})
</script>
