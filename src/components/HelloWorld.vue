<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
   <svg-icon icon-class="home" :class-name="svgClass"></svg-icon>
   <svg-icon icon-class="close" :class-name="svgClass"></svg-icon>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      svgClass: 'f30'
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
.f30{
  font-size: 40px;
}
</style>
