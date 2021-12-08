<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      You can checkout this project source from github:
      <a href="https://github.com/corasphinx/Emaww.git" target="_blank" rel="noopener">download source from git</a>.
    </p>
    <h3>Export xml to 
      <a href="https://redis.io/" target="_blank" rel="noopener">Redis</a>.
    </h3>
    <ul>
      <li><button v-on:click="exportXML">Export</button></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  // define methods under the `methods` object
  methods: {
    exportXML: function () {
      
    }
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
button {
  background-color: #42b983;
  color: #FFFFFF;
  width: 200px;
  height: 50px;
  border-width: 0px;
}

</style>
