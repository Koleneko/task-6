<template>
  <div id="app">
    <div id="nav">
      <router-link to="/pagination">Pagination</router-link>
      <router-link to="/virtualscroll">Virtual Scroll</router-link>
      <router-link to="/sort">With sort</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-right: 30px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
