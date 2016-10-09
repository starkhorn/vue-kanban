<template>
<div id="app">
  <section class="hero is-fullheight">
    <div class="hero-body">
      <div class="container">
        <div class="header">
          <h1 class="title is-1">Vue Kanban</h1>
        </div>

        <div class="tile is-ancestor">
          <Lane title="TODO" />
          <Lane title="In Progress" />
          <Lane title="Done" />
        </div>
      </div>

    </div>
  </section>
</div>
</template>

<script>
import Lane from './components/Lane';

export default {
  components: {
    Lane
  }
};
</script>

<style lang="scss">@import 'node_modules/bulma/bulma';</style>

<style scope>
.header {
  margin-bottom: 20px;
}
</style>
