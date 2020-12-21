<template>
  <div class="home">
    <img alt="En pony" src="../assets/placeholder.png">
    <HelloWorld msg="Velkommen til mit portfolio"/>
<section>
<ul class="listthingie">
<li><router-link to="/enlillebilledviser"><bubble msg="En lille billedviser" data-tooltip="Mobilt billedgalleri i React" /></router-link></li>
<li><bubble msg="Find kattene" data-tooltip="Spil for de mindste"/></li>
<li><bubble msg="Er det tid nu?" data-tooltip="Tæl ned til din favorit begivenhed"/></li>
<li><bubble msg="Hvor får?" data-tooltip="Et spil med ... får"/></li>
<li><bubble msg="Light, Dark, Dork Switcher" data-tooltip="Lyst, mørkt eller nørdet?"/></li>
<li><bubble msg="Er det jul nu?" data-tooltip="Den oprindelige nedtællings app"/></li>
<li><bubble msg="Det himmelske lys" data-tooltip="Lys-styrings app"/></li>
</ul>
</section>
  
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

@keyframes example {
  from {
    transform: translate(1200px, 0);
    opacity: 0.1;
}
to {
transform: translate(5px, 0);
opacity: 1;
}

}

li{
position: relative;
animation-name: example;
animation: example 0.5s linear;
}






</style>
