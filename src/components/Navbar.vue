<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
        <li>Home</li>
        <li>Posts</li>
        <li>Contahct</li>
        <li>About</li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'Navbar',
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
