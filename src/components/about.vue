<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <img class="b-lazy" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="https://placehold.it/1024x1024" alt="Vue.js PWA">
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'About jB view'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
* {
  color: red;
}
</style>
