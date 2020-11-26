<template>
  <div id="nav" style="display: flex;justify-content: center;">
    <a href="/">Navigation</a> |
    <a href="/signin">Bar</a>
  </div>

  <router-view/>

  <div id="end-container">
    <div id="end-text">Hacker Overflow</div>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {

  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
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

  #end-container{
    margin-top: 135px;
    background-color: #f7f7f7;
    width: 100%;
    height: 323px;
    display: flex;justify-content: center;align-items: center;
  }

  #end-text{
    font-size: 25px;
    font-weight: bolder;
  }

</style>
