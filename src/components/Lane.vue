<template lang="html">
  <div class="tile is-4 is-parent">
    <div class="tile is-child box lane">
      <div class="title is-5">
        {{title}}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  }
};
</script>

<style lang="scss" scope>
.lane {
  height: 70vh;
}
</style>
