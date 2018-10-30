<template>
  <div class="hello">

    <h3>Social Links</h3>
    <ul>
      <li><a href="https://www.facebook.com/mahesh.shahi.7927" target="_blank" rel="noopener">FaceBook</a></li>
      <li><a href="https://www.linkedin.com/in/mahesh-shahi-51a02293/" target="_blank" rel="noopener">LinkedIn Chat</a></li>
      <li><a href="mailto:leotempshahi@gmail.com" target="_blank" rel="noopener">Email Me</a></li>
      <li><a href="https://github.com/leoshahi" target="_blank" rel="noopener">Github</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    name: String
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
