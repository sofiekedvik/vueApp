<template>
  <div class="container">
    <h1>{{ msg }}</h1>
    <h2>{{ preamble }}</h2>
    <p> So for start I'll list what a nice portfolio could contain</p>
    <ul class="list list--bullet">
      <li>A skill tree, where you could measure you skillset in a diagram</li>
      <li>A section where you describe your self, your strength, beliefs or dreams</li>
      <li>Some quotes or links to stuff you enjoy to read, maybe within your work field</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Start',
  data () {
    return {
      msg: 'Welcome to this doodle Portfolio',
      preamble: 'This was made only to try out Vue.js'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
