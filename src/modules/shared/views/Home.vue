<template>
  <h1>Home Prova</h1>
</template>

<script lang="ts" setup>
  import { staticTables } from '@/store/staticTables'

  const pinia = staticTables()

  pinia.breadcrumbsItems = null
</script>

<style lang="scss"></style>
