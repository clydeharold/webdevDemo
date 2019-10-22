<template>
  <div id="app">
    <div class="wrapper">
      <vueSideBar/>
      <div id="content">
        <vueNavBar/>
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import vueSideBar from './components/vueSideBar'
import vueNavBar from './components/vueNavBar'
import vuePageHome from './components/vuePageHome'
export default {
  name: 'App',
  components: {
    HelloWorld,
    vueSideBar,
    vueNavBar,
    vuePageHome
  }
}
</script>

<style src="./assets/css/style.css">
</style>
