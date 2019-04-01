<template>
  <div id="app">
    <PinchImage :src="testImg" :min-zoom="1" :max-zoom="2.5"/>
  </div>
</template>

<script>
import PinchImage from './components/PinchImage'

export default {
  name: 'app',
  data() {
    return {
      testImg : 'https://assets.pernod-ricard.com/nz/media_images/test.jpg?hUV74FvXQrWUBk1P2.fBvzoBUmjZ1wct'
    }
  },
  components: {
    PinchImage
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
