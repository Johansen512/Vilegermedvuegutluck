<template>

  <button class="bubble">
  <p>{{ msg }}</p>
    <slot/>
  </button>




</template>

<script>
export default {
props: {
    msg: String
    
  }
}

</script>

<style scoped>


  .bubble {
    display:inline-block;
    
    margin: 1.5em;
    padding: 1em 2em;
    background: lightblue;
    width: 150px;
    height: 150px;
    border: 2px solid tomato;
    border-radius: 50%;
    color: tomato;
    font-family: "Quicksand", sans-serif;
    font-size: 1em;
    font-weight: 700;
    letter-spacing: 0.02em;
    line-height: 1;
    text-decoration: none;
    text-transform: uppercase;
    cursor: pointer;
    transition: 0.3s;
  }

  .bubble:hover {
    background: blue;
    width: 300px;
    height: 300px;
    
  }
.bubble:hover::after{
content: attr(data-tooltip);
}

</style>