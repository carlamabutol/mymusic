<template>
  <div class="app-container p-3 bg-black m-auto">
    <SongList />
  </div>
</template>

<script>
import SongList from './components/SongList.vue';

export default {
  name: 'App',
  components: {
    SongList
  }
}
</script>

<style>
body {
  font-family: sans-serif;
}
.app-container {
  width: 100%;
  height: 50%;
  padding-top: -30px;
  padding-left: 50px;
  padding-right: 50px;
  padding-bottom: 50px;
  border-color: gold;
  border-width: 2px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
