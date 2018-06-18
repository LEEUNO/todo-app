<template>
  <div id="app">
    <main-header></main-header>
    <router-view></router-view>
  </div>
</template>

<script>
import router from './router'
import MainHeader from '@/components/MainHeader'

export default {
  name: 'app',
  data () {
    return {
    }
  },
  components: {
    MainHeader,
  }
}
</script>

<style lang='scss'>
* {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing : border-box;
}
html {
  width: 100%;
  height: 100%;
  font-size: 16px;
}

#app {
  font-family: 'Nanum Gothic', 'Roboto', sans-serif;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
}
/*
h1, h2 {
  font-weight: normal;
} */

ul {
  list-style-type: none;
  padding: 0;
}

li {
  /* display: inline-block; */
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
