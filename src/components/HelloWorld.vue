<template>
  <div class="yokoponzoo-top">
    <yokoponzoo-header />
    <div class="yokoponzoo-content">
      <yokoponzoo-main />
      <hr>
      <yokoponzoo-education />
      <hr>
      <yokoponzoo-interests />
      <hr>
      <yokoponzoo-skills />
      <hr>
      <yokoponzoo-works />
    </div>
    <yokoponzoo-footer />
  </div>
</template>

<script>
import Footer from './Footer'
import Header from './Header'
import Main from './Main'
import Education from './Education'
import Skills from './Skills'
import Works from './Works'
import Interests from './Interests'

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      test: 'test'
    }
  },
  components: {
    'yokoponzoo-footer': Footer,
    'yokoponzoo-header': Header,
    'yokoponzoo-main': Main,
    'yokoponzoo-education': Education,
    'yokoponzoo-skills': Skills,
    'yokoponzoo-works': Works,
    'yokoponzoo-interests': Interests
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.yokoponzoo-content {
  max-width: 750px;
  margin: auto;
}
</style>
