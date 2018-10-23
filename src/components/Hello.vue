<template>
  <div class="hello">
    <h1>site : {{site}}</h1>
    <h1>url : {{url}}</h1>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      site: '菜鸟教程',
      url: 'www.runoob.com',
      alexa: '10000'
    }
  }
}
</script>
