<script setup lang="ts">
</script>

<script>
export default {
  props: ['title', 'items']
}
</script>

<template>
  <h2 class="fs-4 my-2">{{ title }}</h2>
  <ul>
    <li v-for="item in items">{{ item }}</li>
  </ul>
</template>

<style>
</style>
