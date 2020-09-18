<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Test msg="Welcome to Your Vue.js App"></Test>
  </div>
</template>

<script>

import Test from './components/Test.vue'

export default {
  name: 'App',
  components: {
    Test
  }
}
</script>

<style>

</style>
