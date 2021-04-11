<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <InputSection dateOfTrip="01.01.2021" hourOfTrip="13" locationText="Hemsedal"/>
  
<!-- dateOfTrip,
        hourOfTrip,
        locationText, -->

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import InputSection from './components/InputSection.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    InputSection
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
