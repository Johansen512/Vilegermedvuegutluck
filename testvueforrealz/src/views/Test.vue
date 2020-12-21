<template>

 <div id="hello-vue" class="demo">
  {{ message }}
</div>


  
</template>

<script>
// @ is an alias to /src


export default {



  name: 'Test',
  components: {
    
    
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

Vue.createApp(HelloVueApp).mount('#hello-vue')

