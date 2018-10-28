<template>
  <div id="app">
        <AppToolbar></AppToolbar>
    <router-view></router-view>
    <AppFooter></AppFooter>
  </div>
</template>

<style>
#app {
  font-family: 'Roboto', 'Lato', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: #4e87ee;
}


</style>
<script>
// @ is an alias to /src
import AppToolbar from '@/components/AppToolbar.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
  name: 'home',
  components: {
    AppToolbar,
    AppFooter
  }
}
</script>

