<template>
<HelloVueApp >
<div id="hello-vue" class="demo">
  {{ message }}
</div>

</HelloVueApp >
</template>


<script>
// @ is an alias to /src


export default {
components: {
  
    
    HelloVueApp
  },
 
  props: {
    message: String
  }

};

const HelloVueApp = {
  data() {
    return {
      message: 'Hello Vue!!'
    }
  }}




</script>



<style scoped>


  .demo{
   
    border: 2px solid tomato;
  
}
</style>