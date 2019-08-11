<template>
  <div id="app">
    <CountryPicker/>
  </div>
</template>

<script>
import CountryPicker from './components/CountryPicker.vue';

export default {
  name: 'app',
  components: {
    CountryPicker,
  },
};
</script>
<style lang="stylus">
#app
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>
