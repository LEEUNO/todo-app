<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import router from './router'

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang='scss' scoped>
* {
  padding: 0;
  margin: 0;
  border: 0;
}

#app {
  font-family: 'Nanum Gothic', 'Roboto', sans-serif;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
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
