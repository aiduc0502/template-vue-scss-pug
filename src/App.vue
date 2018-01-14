<template lang="pug">
  #app
    img(src="./assets/logo.png")
    h1 {{msg}}
    h2 Test
    ul
      li
        a(href="https://vuejs.org" target="_blank") Vuejs
      li
        a(href="https://vuejs.org" target="_blank") Angularjs
      li
        a(href="https://vuejs.org" target="_blank") Reactjs
      li
        a(href="https://vuejs.org" target="_blank") React Native  
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  h1 {
    color: red;
  }
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
