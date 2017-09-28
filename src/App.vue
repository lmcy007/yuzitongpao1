<template>
  <div id="app">
    <article0/>
    <creation/>
  </div>

</template>

<script>
  import article0 from './components/article0'
  import creation from './views/creation'
  export default {
    name: 'app',
    components: {article0, creation}
  }
</script>
<style scoped>
  #app {
    margin:0 auto;border:1px solid #fff;width:80%;height:200%;
          }
  body{

  }
</style>

