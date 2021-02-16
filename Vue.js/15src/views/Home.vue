<template>
  <div>
    <h1> Singer Songwriter</h1>
    <RoyKim />
  </div>
  
  
</template>

<script>
import RoyKim from '@/components/RoyKim.vue';

export default {

  components:{
    RoyKim
  },
  data(){
    return{
      name: 'Roy Kim'
    }
  }
}
</script>

<style scoped>
h1{
  color:darkblue;
}
</style>