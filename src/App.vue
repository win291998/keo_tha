<template>
  <div id="app">
    <CardList />
  </div>
</template>

<script>
import CardList from './components/CardList.vue'

export default {
  name: 'App',
  components: {
    CardList,
  }
}
</script>

<style>
#app {
 display: flex;
 justify-content: space-evenly;
 align-items: center;
 font-family: "Roboto", sans-serif;
 -webkit-font-smoothing: antialiased;
 -moz-osx-font-smoothing: grayscale;
}
:root {
 font-size: 10px;
}
</style>
