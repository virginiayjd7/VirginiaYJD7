<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
       En proceso de construcción 💙
    </p>
    <h3>My Skills</h3>
    <ul>
      <li><a href="">Linux</a></li>
      <li><a href="">Docker</a></li>
      <li><a href="">Kubernetes</a></li>
    </ul>
    <h3>My Projects</h3>
    <ul>
      <li><a href="https://github.com/virginiayjd7/Proyecto_Agroite_V2" target="_blank" rel="noopener">AgroIte</a></li>
      <li><a href="https://github.com/virginiayjd7/PruebaGithub-Actions" target="_blank" rel="noopener"> PruebaGithub-Actions </a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
