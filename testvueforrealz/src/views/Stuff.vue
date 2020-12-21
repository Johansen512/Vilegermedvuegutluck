<template>

  <div class="about">
    <h1>This is an stuff page</h1>

    <p>Og her kommer alt muligt sandkasse</p>
<bholder>
    <btn1 />
    <btn1 />
    <btn1 />
</bholder>

<testdims />

</div>
  
</template>

<script>
// @ is an alias to /src
import bholder from '@/components/bholder.vue'
import testdims from '@/components/testdims.vue'
export default {



  name: 'Stuff',
  components: {
  
    
    testdims,
    bholder
  }
  



 
}






</script>


