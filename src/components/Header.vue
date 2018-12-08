<template>
  <nav class="navbar is-dark" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item yokoponzoo-logo" href="#">
        <img src="../../static/yokoponzoo.png" width="112" height="28" class="">
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      isBurgerActive: false
    }
  },
  methods: {
    toggleBurgerState () {
      this.isBurgerActive = !this.isBurgerActive
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.yokoponzoo-logo {
  margin: auto;
}
</style>
