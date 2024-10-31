<template>
  <div id="app">
    <SearchCity/>
  </div>
</template>

<script>
import SearchCity from './components/SearchCity.vue'

export default {
  name: 'App',
  components: {
    SearchCity
  }
}
</script>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}
</style>
