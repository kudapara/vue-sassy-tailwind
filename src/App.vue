<template>
  <div id="app">
    <img src="./assets/logo.png">
    <button id="app__btn">Hello</button>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="sass">
  @import "./assets/scss/app.scss"
</style>
