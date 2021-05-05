<template>
  <div>
    <h1>This is Home page</h1>
    <Cheongdo />
  </div>
</template>

<script>
import Cheongdo from '@/components/Cheongdo.vue';

export default {
  components: {
    Cheongdo
  },

  data() {
    return {
     
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>
