<template>
  <button class="btnNew" @click="increment">
    Count is: {{ count }}, double is {{ double }}, click to increment.
  </button>

  <h2 id="result"></h2>
</template>

<script>
import { ref, computed, onMounted } from 'vue'

export default {
  setup() {
    const count = ref(0)
    const double = computed(() => count.value * 2)

    function increment() {
      count.value++

      if ( count.value % 2 == 0) {
	document.getElementById('result').innerHTML = ' LIGE! SIR JEG JU!';
}else{
	document.getElementById('result').innerHTML = ' Ulige';
}
    }

    onMounted(() => console.log('component mounted!'))

    return {
      count,
      double,
      increment
    }
  }
}
</script>

<style>

.btnNew{
display:inline-block;
    
    margin: 0.5em;
    padding: 0.5em;
    background: orange;
    width: 150px;
    height: 150px;
    border: 2px solid #1661a7;
    border-radius: 20%;
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
    outline: none;
}
</style>