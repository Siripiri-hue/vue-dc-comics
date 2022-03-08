<template>
  <div id="app">
    <DcHeader/>
    <BlueBanner/>
    <MainContents/>
    <DcFooter/>
    <SocialBanner/>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import DcHeader from './components/DcHeader.vue'
import BlueBanner from './components/BlueBanner.vue'
import MainContents from './components/MainContents.vue'
import DcFooter from './components/DcFooter.vue'
import SocialBanner from './components/SocialBanner.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    DcHeader,
    BlueBanner,
    MainContents,
    DcFooter,
    SocialBanner
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
