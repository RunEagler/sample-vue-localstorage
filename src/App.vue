<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div id="container">
      <LocalStorageEntry></LocalStorageEntry>
      <LocalStorageGet></LocalStorageGet>
    </div>
  </div>
</template>

<script>
import LocalStorageEntry from './components/LocalStorageEntry'
import LocalStorageGet from './components/LocalStorageGet'

export default {
  name: 'App',
  components: {
    LocalStorageEntry,
    LocalStorageGet
  }
}
</script>

<style>

  #container {
    display: grid;
    grid-template-columns: 500px 1fr;
  }
</style>
