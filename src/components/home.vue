<template>
  <div class="home">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'home page view'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

p {
  color: green;
}
</style>
