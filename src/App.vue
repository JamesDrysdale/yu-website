<template>
  <Header />
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
</template>

<script>
import Header from '../src/components/Header'


export default {
  name: 'Home',
  components: {
    Header
  }
}


</script>

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
}

#nav a.router-link-exact-active {
  color: #42b983;
}

body {
    font-family: 'Open Sans', sans-serif;
    /* background-color: #E1E8ED; */
    font-size: 16px;
    color: #324B4A;
    background: url("../src/assets/yu-bg.png");
    background-repeat: repeat;
    margin: 0px;
}


</style>
