<template>
    <nav class="navbar navbar-default" id="alex" role="navigation">
      <img src="./assets/logo.png" class="gambar">
      <navbar>
        <router-link to="/" class="active" style="display:flex;">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/login">login</router-link>
        </navbar>
    
  </nav>
  <router-view/>
</template>

<style>
#alex{
  display: grid;
  grid-template-columns: 1fr 1fr;
  border:0px solid;
}
  .gambar{
    width:40px; height:40px;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

navbar {
  display: grid;
  border:0px solid;
  grid-template-columns: 1fr 2fr 1fr;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
