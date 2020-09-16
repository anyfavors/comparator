<template>
  <Comparison></Comparison>
</template>

<script>
import Comparison from './components/Comparison.vue'

export default {
  name: 'App',
  components: {
    Comparison
  }
}
</script>

<style>
/* --------------------------------

Primary style

-------------------------------- */
*, *::after, *::before {
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
}

body {
  font-size: 1.6rem;
  font-family: "Source Sans Pro", sans-serif;
  color: #404042;
  background-color: #ffffff;
}

a {
  color: #9dc997;
  text-decoration: none;
}

img {
  max-width: 100%;
}

h1 {
  font-size: 2.2rem;
  text-align: center;
  padding: 4em 5%;
}
@media only screen and (min-width: 1170px) {
  h1 {
    font-size: 4rem;
    font-weight: 300;
    padding: 3em 5%;
  }
}
</style>
