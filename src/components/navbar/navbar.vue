<template>
  <div class="nav">
    <b-navbar toggleable="lg" type="light" variant="white" class="nav-content">
      <b-navbar-brand href="#" class="nav-brand">
        <img src="./img/logo.png" class="nav-logo" />
      </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav class="nav-coll">
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Portfolio</b-nav-item>
          <b-nav-item href="#">Team</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  date: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import './index.scss'
</style>
