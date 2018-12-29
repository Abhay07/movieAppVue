<template>
  <div class="App">
        <header class="header">Movies of 2018 (Vue)</header>
        <MovieList />
  </div>
</template>

<script>
import MovieList from './components/MovieList.vue'

export default {
  name: 'app',
  components: {
    MovieList
  }
}
</script>

<style>
  @import './App.css';
</style>
