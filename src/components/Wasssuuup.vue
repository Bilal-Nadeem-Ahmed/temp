<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide on how to get to a million quid in a week,<br>
      check out the
      <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    
  </div>
</template>

<script>
export default {
  name: 'Wasssuuup!',
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
