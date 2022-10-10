<template>
  <p> Exercise 3: The newly generated project contains a few placeholders. 
    Cleanup your project so it does not contain neither useless assets, nor the hello world. 
    In other words, delete HelloWorld.vue, its related assets and all its references. 
    As at the end of each exercise, the vue cli should not report any error or warning.
  </p>
  <HomePage/>
</template>

<script>
import HomePage from './components/HomePage.vue'
export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>

</style>
