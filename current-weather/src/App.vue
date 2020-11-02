<template>
  <div id="app">
     <div>
       <SearchWeather />
     </div>
    <div>
       <CurrentWeather nomVille="Nantes" temperature="50"/>
    </div>
  </div>
</template>

<script>
import CurrentWeather from './components/CurrentWeather.vue'
import SearchWeather from './components/SearchWeather.vue'


export default {
  name: 'App',
  components: {
    CurrentWeather,
    SearchWeather
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
