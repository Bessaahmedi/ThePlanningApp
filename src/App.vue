<template>
  <div class="container">
    <Header />
    <Frontpage />
  </div>
</template>

<script>
import Header from './components/Header'
import Frontpage from './components/Frontpage'

export default {
  name: 'App',
  components: {
    Header,
    Frontpage,
  },
}
</script>

<style>
/* Global Stylesheet - counts for all of the components */
* {
  font-family: Arial, Helvetica, sans-serif;

    margin: 0;
    padding: 0;
    box-sizing: border-box;

  text-decoration: none;
  color: black;
}

.container {
  max-width: 500px;
  margin: 0 auto;
  overflow: auto;
  height: auto;
}
</style>
