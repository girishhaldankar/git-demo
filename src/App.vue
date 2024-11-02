<template>
  
  <MapBox/>
</template>

<script>
import MapBox from './components/MapBox.vue'
import '../node_modules/mapbox-gl/dist/mapbox-gl.css';

export default {
  name: 'App',
  components: {
    MapBox
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
  margin-top: 60px;
}
</style>
