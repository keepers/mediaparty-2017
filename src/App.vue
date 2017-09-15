<template>
  <div id="app">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="http://bulma.io">
          <img src="./assets/logo.png">
          Media Party
        </a>
        <div class="navbar-burger">
          {{ $route.name.toUpperCase() }}
        </div>
      </div>
    </nav>
    <router-view class="app-container"></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.navbar {
  background-color: #eee;
}

.app-container {
  margin-top: 60px;
  padding: 0 2em;
}
</style>
