<template lang="html">
  <div class="tile is-ancestor">
    <Lane v-for="title in lanes" :title="title" />
  </div>
</template>

<script>
import Lane from './Lane';

export default {
  props: {
    lanes: Array
  },

  components: {
    Lane
  }
};
</script>

<style lang="css">
</style>
