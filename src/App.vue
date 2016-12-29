<template>
  <div id="app">
    <Start></Start>
    <Foot></Foot>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Start from './components/Start'
import Foot from './components/Footer'

export default {
  name: 'app',
  components: {
    Hello,
    Foot,
    Start
  }
}
</script>

<style src="./css/style.css">
</style>
