<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <btn1 msg="hvad med her"/>
  </div>

  

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import btn1 from '@/components/btn1.vue'
export default {
  name: 'Home',
  components: {
    HelloWorld,
    btn1
  }
}
</script>
