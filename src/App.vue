<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <div class="text-center">
      <a id="app__btn" href="https://vuejs.org">Visit the vue website</a>
    </div>
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
