<template>
  <div id="app">
    <appHeader/>
    <main>
      <app-jumbo/>
      <app-col/>
      <app-courses/>
      <app-main/>
      <app-second-jumbo/>
    </main>
    <app-footer/>
  </div>
</template>

<script>
import dati from './dati.json'
import AppFooter from './components/appFooter.vue'
import appHeader from './components/appHeader.vue'
import AppMain from './components/appMain.vue'
import AppJumbo from './components/AppJumbo.vue'
import AppCol from './components/AppCol.vue'
import AppCourses from './components/AppCourses.vue'
import AppSecondJumbo from './components/AppSecondJumbo.vue'


export default {
  name: 'App',
  components: {
    appHeader,
    AppJumbo,
    AppCol,
    AppFooter,
    AppMain,
    AppCourses,
    AppSecondJumbo,
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
