<script setup lang="ts">
import Sidebar from '../components/Sidebar.vue'
import CV from '../components/CV.vue'
</script>

<template>
  <main class="d-md-flex">
    <Sidebar />
    <CV />
  </main>
</template>

<style>


main {
  height: 100vh;
  height: -webkit-fill-available;
  max-height: 100vh;
  overflow-x: scroll;
  overflow-y: scroll;
}

.scrollarea {
  overflow-y: auto;
}

a {
  color: white;
}

.main-section {
  background-color: #191919 !important;
  overflow-y: scroll;
}

.sidebar {
  overflow-y: scroll;
}

.container {
  max-width: 700px;
}

.content {
  border: 2em;
}

</style>