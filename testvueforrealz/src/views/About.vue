<template>
  <div class="about">
    <h1>This is an about page</h1>

    <p>Og her kommer alt mit snas</p>
<bholder>
    <btn1 msg="En"/>
    <btn1 msg="To"/>
    <btn1 msg="Tre"/>
</bholder>

  </div>
</template>

<script>
// @ is an alias to /src

import bholder from '@/components/bholder.vue'
export default {
  name: 'About',
  components: {
   
    bholder
  }
}
</script>


