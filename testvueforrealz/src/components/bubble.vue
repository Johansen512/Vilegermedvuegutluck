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
    
    margin: 0.5em;
    padding: 0.5em;
    background: lightblue;
    width: 150px;
    height: 150px;
    border: 2px solid #1661a7;
    border-radius: 50%;
    color: #0c3963;
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
    background: #1c84e5;
    width: 180px;
    height: 180px;
    
  }
.bubble:hover::after{
content: attr(data-tooltip);
font-size: 0.9em;
border: 4px;
}

</style>