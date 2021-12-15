<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div>{{ variable1 }}</div>
  <div>{{ variable2 }}</div>
</template>

<script>
import getEnv from '@/utils/env'

export default {
  name: 'App',
 data() {
    return {
      variable1: getEnv('VUE_APP_VARIABLE_1'),
      variable2: getEnv('VUE_APP_VARIABLE_2')
    }
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
