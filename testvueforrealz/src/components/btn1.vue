<template>

  <button class="button">
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


  .button {
    display:inline-block;
    
    margin: 1.5em;
    padding: 1em 2em;
    background: #fff;
    border: 2px solid tomato;
    border-radius: 3px;
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

  .button:hover {
    background: tomato;
    color: #fff;
  }
</style>