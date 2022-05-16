<template>
  <div id="app">
    <appHeader/>
    <main>
      <app-main/>
    </main>
    <app-footer/>
  </div>
</template>

<script>
import dati from './dati.json'
import AppFooter from './components/appFooter.vue'
import appHeader from './components/appHeader.vue'
import AppMain from './components/appMain.vue'

export default {
  name: 'App',
  components: {
    appHeader,
    AppFooter,
    AppMain,
  },
  data(){
    return{
       myDati: dati
      
    }
    

  }
}
</script>

<style lang="scss">
@import "./styles/general.scss";
</style>
