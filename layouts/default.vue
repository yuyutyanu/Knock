<template>
  <div class="container">
    <nuxt/>
  </div>
</template>
<script>

</script>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}
.container{
  min-width:320px;
  background: #f8f8f8;
}
@media (min-width:480px) {
  .container{
    max-width:800px;
    margin:0 auto;
  }
}

</style>
