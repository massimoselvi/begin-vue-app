<template>
  <div class="hello">
    <h1>{{ message }}</h1>
    <h2>My Begin Profile</h2>
    <p>
      demo created with Begin ...
      <a href="https://begin.com/massimoselvi" target="_blank" rel="noopener">massimoselvi</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    message: String
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
