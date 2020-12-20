<template>

<div class="bholder">
<btn1 msg="1"/>
<btn1 msg="2"/>
<btn1 msg="3"/>
</div>




</template>

<script>
import btn1 from '@/components/btn1.vue'
export default {
name: 'bholder', 

 components: {
   
    btn1
  }, 
   props: {
    msg: String
  }

  

  
}

</script>

<style scoped>

.bholder{
display:flex;
flex-direction: row;
justify-content: center;
align-items: center;
border: solid black 10px;

}
 
</style>