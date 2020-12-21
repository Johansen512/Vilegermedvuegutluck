<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
    En lille, mobile-first billedviser kodet i React
    </p>

    <p>Kendt fejl i version 1: </p>
    <p>Værktøjer: HTML, CSS, JavaScript, React</p>

    <a href="https://enlillebilledviser.netlify.app/"><button>Prøv den!</button></a>
   
  </div>

  
</template>

<script>
export default {
  name: 'enlillebilledviser',
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


.button {

border: solid red 2px;
}

 
</style>
