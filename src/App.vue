<template>
  <div id="app">
    <appHeader/>
    <main>

    </main>
    <app-footer/>
  </div>
</template>

<script>
import AppFooter from './components/appFooter.vue'
import appHeader from './components/appHeader.vue'

export default {
  name: 'App',
  components: {
    appHeader,
    AppFooter,
  }
}
</script>

<style lang="scss">
@import "./styles/general.scss"
</style>
