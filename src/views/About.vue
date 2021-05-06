<template>
  <div class="about">
    <h1>This is an about page</h1>
    <Cheongdo >
      <template #header="{ cheongdo }">
        <p>Header!!2 {{ cheongdo }} </p>
      </template>
      <template #default>
        hello!
      </template>
    </Cheongdo>
  </div>
</template>

<script>
import Cheongdo from '@/components/Cheongdo.vue';

export default {
  components: {
    Cheongdo
  },
}

</script>

