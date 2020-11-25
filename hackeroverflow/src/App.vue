<template>
  <div id="nav" style="display: flex;justify-content: center;">
    <a href="">Navigation</a> |
    <a href="">Bar</a> |
    <a href="">To</a> |
    <a href="">Make</a>
    <a href="">Copy code only</a>
    <a href="">So No Problem</a>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-left: 20px;
  margin-right: 20px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
