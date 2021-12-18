<template>
  <div class="container">
    <Header />
    <Kalenderikon />
   
    
  </div>
</template>

<script>
import Header from './components/Header'
import Kalenderikon from './components/Kalenderikon'

export default {
  name: 'App',
  components: {
    Header,
    Kalenderikon,
  },
}
</script>

<style>
/* Global Stylesheet - counts for all of the components */
* {
  font-family: Arial, Helvetica, sans-serif;

    margin: 0;
    padding: 0;
    overflow: hidden;

}

.container {
  max-width: 500px;
  margin: 0 auto;
  overflow: auto;
  min-height: 300px;
  border-radius: 5px;
}
</style>
