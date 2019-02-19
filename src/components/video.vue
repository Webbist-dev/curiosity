<template>
  <div class="video">
    <video muted autoplay loop>
      <source :src="`${publicPath}video/mars.mp4`" type="video/mp4">
    </video>
  </div>
</template>
   
<script>
  export default {
    name: 'MarsVideo',
    data () {
      return {
        publicPath: process.env.BASE_URL
      }
    }
  }
</script>

<style land="scss" scoped>
  .video {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    z-index: -1;
    border-radius: 50%;
    width: 700px;
    height: 700px;
    -webkit-mask-image: -webkit-radial-gradient(circle, white 100%, black 100%);
  }

  video {
    max-width: 150%;
  }
</style>

 
