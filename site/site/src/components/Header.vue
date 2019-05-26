<template>
  <!-- Header -->
  <div id="header">
    <span class="logo icon fa-paper-plane-o"></span>
    <h1>Hi. This is Directive.</h1>
    <p>A responsive HTML5 + CSS3 site template designed by <a href="http://html5up.net">HTML5 UP</a>
    <br />
    and released for free under the <a href="http://html5up.net/license">Creative Commons license</a>.</p>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
