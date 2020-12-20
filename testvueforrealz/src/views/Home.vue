<template>
  <div class="home">
    <img alt="En pony" src="../assets/placeholder.png">
    <HelloWorld msg="Velkommen til mit portfolio"/>
<nav>
<ul>
<li><bubble msg="test" data-tooltip="testing testing" /></li>
<li><bubble msg="test2" data-tooltip="testing testing2"/></li>
<li><bubble msg="test3" data-tooltip="testing testing3"/></li>
<li><bubble msg="test4" data-tooltip="testing testing4"/></li>
<li><bubble msg="test5" data-tooltip="testing testing5"/></li>
<li><bubble msg="test6" data-tooltip="testing testing6"/></li>
<li><bubble msg="test7" data-tooltip="testing testing7"/></li>
</ul>
</nav>
    <btn1 msg="hvad med her"/>
  </div>

  

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import btn1 from '@/components/btn1.vue'
import bubble from '@/components/bubble.vue'
export default {
  name: 'Home',
  components: {
    HelloWorld,
    btn1,
    bubble
  }
}
</script>

<style scoped>
nav{

}

ul{
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;


}

</style>
