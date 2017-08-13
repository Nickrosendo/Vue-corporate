<template>
  <div id="app">
    <octadesk-header></octadesk-header>

  </div>
</template>

<script>
import Menu from './components/Menu.vue'
export default {
  name: 'app',
  components: {
    'octadesk-header': Menu
  }
}
</script>
<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Just+Another+Hand|Lato:300,400,700');

  //
  // Globally
  //

  html, body {
    width: 100vw;
    height: 100vh;
    max-width:100%;
    margin: 0;
    padding: 0;
    font-weight: 300;
    font-size: 16px;
  }
  h1, h2, h3, h4, h5, h6,
  .h1, .h2, .h3, .h4, .h5, .h6 { font-weight: 700; }
  strong { font-weight: 500; }
  .bold{ font-weight: 700; }
  a{
    color:  rgba(0, 0, 0, 0.5);
    text-decoration: none !important;
    &hover{
      color: rgba(0, 0, 0, 0.7);
      text-decoration: none !important;
      cursor: pointer !important;
    }
  }

</style>
