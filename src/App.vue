<template>
  <YuHeader />

  <YuFooter />
</template>

<script>
import YuHeader from '../src/components/YuHeader'
import YuFooter from '../src/components/YuFooter'


export default {
  name: 'Home',
  components: {
    YuHeader,
    YuFooter
  }
}


</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,400;0,700;0,900;1,400;1,700;1,900&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');

#app {
  font-family: 'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
    font-size: 16px;
    color: #324B4A;
    background: url("../src/assets/yu-bg.png");
    background-repeat: repeat;
    margin: 0px;
}

a {
    text-decoration: none;
}


</style>
