<!--
  // Created on Tue Jul 10 2018
  // Copyright © 2017-2018 Mikhail K. (iSm1le)
  // Licensed under the Apache License, Version 2.0
  -->
<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import YoutubeRV from './components/YoutubeRV';

export default {
  name: 'App',
  components: {
    YoutubeRV
  }
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed:400,400i,700|Material+Icons'); // Roboto Condensed font

* {
  box-sizing: border-box;
  font-family: 'Roboto Condensed', sans-serif;
  font-weight: 400;
}

html, body, #app {
  width: 100%;
  height: 100%;
  background-color: #2c3e50;
  margin: auto;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
