<template>
  <div>
    <h1>Vue 3 Project</h1>
    <TableComponent />
    <JSXComponent />
    <AppComponent />
  </div>
</template>

<script lang="ts">
export default {
  name: 'App'
}
</script>

<script lang="ts" setup>
import TableComponent from '@vue3Base/TableComponent'
import JSXComponent from '@vue3Base/JSXComponent'
import AppComponent from '@vue3Base/AppComponent'
</script>

<style lang="less" scoped></style>
