<template>
  <div id="app" class="jBGrid">
    <nav>
      <a href="/">Home</a>
      <a href="#about">About</a>
      <a href="#sites">Sites</a>
    </nav>
    <header><h1>jB</h1></header>
    <main id="mainContent">
      <router-view></router-view>
    </main>
    <aside>
      Aside
    </aside>
    <footer>
      Footer
    </footer>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">

html {box-sizing: border-box;}
*, *:before, *:after {box-sizing:inherit;}


body {font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen-Sans,Ubuntu,Cantarell,"Helvetica Neue",sans-serif;}

img {max-width: 100%;}


.skipLink {
  position: fixed;
  top: -20rem;
  &:focus {
    top:0;
  }
}

.jBGrid {
  display: grid;
  grid-template-areas:
  'nav nav nav'
  'header header header'
  'aside main main'
  'footer footer footer'
}

nav {grid-area:nav;}
header {grid-area:header;}
main {grid-area: main;}
aside {grid-area: aside;}
footer {grid-area: footer;}

</style>
