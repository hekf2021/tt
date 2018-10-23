<template>
  <div id="app">
    <div v-html="message"></div>
  </div>
</template>

<script type='text/javascript'>
new Vue({
  el: '#app',
  data: {
    message: '<h1>菜鸟教程</h1>'
  }
})
</script>
