<template>
  <div class="about">
    <h1>This is an about page</h1>
    <!-- <RoyKim title="About Title"/> -->
    <RoyKim>
      <template v-slot:header="props">
        <p> header 1111!!! / {{ props.roy }} </p>
      </template>
      <template #default>
        hello mello
      </template>

    </RoyKim>

  </div>
</template>

<script>
import RoyKim from '@/components/RoyKim.vue';
export default {
  components:{
    RoyKim
  }
}
</script>
