<template>
  <div class="hello">
  <apple></apple>
  <second></second>
    hello world
  </div>
</template>

<script>
import apple from '../First'
import second from '../second'

export default {
  name: 'HelloWorld',
  components: {
    apple,
    second,
  },
  props: {
    msg: String
  }
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
</style>
