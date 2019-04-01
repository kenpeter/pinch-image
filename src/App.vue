<template>
  <div id="app">
    <PinchImage :src="testImg" :min-zoom="1" :max-zoom="2.5"/>
    <p>bla</p>
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
    width: 500px;
    height: 500px;
  }

  /*
  .pinch-wrapper {
    width: 500px;
    height: 500px;
  }

  .pinch-img {
    width: 400px;
    height: 400px;
  }
  */

</style>
