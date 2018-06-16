<template>
  <div id="app">
    <NavBar/>
    <ProfileHeader/>
    <Content/>
    <About/>
  </div>
</template>

<script>
import './assets/reset.css'
import NavBar from './components/NavBar.vue'
import ProfileHeader from './components/ProfileHeader.vue'
import Content from './components/Content.vue'
import About from './components/About.vue'

export default {
  name: 'app',
  components: {
    NavBar,
    ProfileHeader,
    Content,
    About
  }
}
</script>

<style>
#app {
  font-family: "Microsoft YaHei", Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-size: 62.5%
}
</style>
