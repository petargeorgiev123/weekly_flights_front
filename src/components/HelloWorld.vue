<template>
  <text class="message">Nowwww {{ name }} , let's use Vue.js to build your Weex app.</text>
</template>

<script>
  export default {
    name: 'list',
    data () {
      return {
        name: "test"
        /*logo: 'https://gw.alicdn.com/tfs/TB1yopEdgoQMeJjy1XaXXcSsFXa-640-302.png'*/
      }
    }
  }
</script>

<style>
  .message {
    margin: 30px;
    font-size: 32px;
    color: #727272;
  }
</style>