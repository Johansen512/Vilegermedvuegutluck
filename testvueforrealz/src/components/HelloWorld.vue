<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
    Her finder du færdige (og mindre færdige) sider, apps, komponenter og dippedutter, som jeg har forsøgt mig med at kode
    </p>
   
  </div>

  <button class="button">Ny test </button>
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

.hello {


}
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

.button {

border: solid red 2px;
}

 
</style>
