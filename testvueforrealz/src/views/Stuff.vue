<template>

  <div class="about">
    <h1>This is an stuff page</h1>

    <p>Og her kommer alt muligt sandkasse</p>
<bholder>
    <btn1 />
    <btn1 />
    <btn1 />
</bholder>



</div>
  <testdims2 />
</template>

<script>
// @ is an alias to /src
import bholder from '@/components/bholder.vue'
import testdims2 from '@/components/testdims2.vue'

export default {



  name: 'Stuff',
  components: {
  
    
    testdims2,
    bholder
  }
  



 
}






</script>


