<template>
  <div class="home">
    <img alt="En pony" src="../assets/placeholder.png">
    <HelloWorld msg="Velkommen til mit portfolio"/>
<nav>
<ul>
<li><bubble msg="En lille billedviser" data-tooltip="Mobilt billedgalleri i React" /></li>
<li><bubble msg="Find kattene" data-tooltip="Spil for de mindste"/></li>
<li><bubble msg="Er det tid nu?" data-tooltip="Tæl ned til din favorit begivenhed"/></li>
<li><bubble msg="Hvor får?" data-tooltip="Et spil med ... får"/></li>
<li><bubble msg="Light, Dark, Dork Switcher" data-tooltip="Lyst, mørkt eller nørdet?"/></li>
<li><bubble msg="Er det jul nu?" data-tooltip="Den oprindelige nedtællings app"/></li>
<li><bubble msg="Det himmelske lys" data-tooltip="Lys-styrings app"/></li>
</ul>
</nav>
  
  </div>

  

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import bubble from '@/components/bubble.vue'
export default {
  name: 'Home',
  components: {
    HelloWorld,
    bubble
  }
}
</script>

<style scoped>
nav{

}

ul{
display: grid;
grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr;


list-style-type: none;


}

</style>
