<template>
  <div id="app">
    <navigation />
    <banner-image />
    <router-view />
  </div>
</template>

<script>
import Navigation from './components/navigation/Navigation'
import BannerImage from './components/Image/BannerImage'

  export default {
    components: {
      Navigation, 
      BannerImage
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
  color: blue;
}

#nav a.router-link-exact-active {
  color: red;
}
</style>
