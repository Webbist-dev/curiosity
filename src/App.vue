<template>
  <div id="app">
    <header class="header container">
      <p>+Instagram</p>
      <h3><a href="#">@madebystudiojq</a></h3>
    </header>

    <div class="container">
      <div class="inner">
        <div class="row">
          <div class="squares"></div>
          <div class="content horizontal-end">
            <h3>Nasa's Mars Rover <br> Oppertunity concludes <br> a 15-year mission</h3>
          </div>
        </div>
        <div class="row">
          <div class="content space-bottom">
            <h3>-Launch date</h3>
            <h4>November 26, 2011, <br>15:02:00 UTC</h4>
          </div>
          <div class="content verticle-end">
            <h3>-Operator</h3>
            <h4>Nasa</h4>
          </div>
        </div>
        <div class="row"></div>
        <div class="row">
          <div class="content horizontal-end">
            <h3>-Distance covered</h3>
            <h4>19.75 km (12.27mi)</h4>
          </div>
        </div>
        <div class="row">
          <h1>-Curiosity <br> (Rover)-.</h1>
        </div>
        <div class="row">
          <div class="content space-left">
            <h3>-Mission type</h3>
            <h4>Mars rover</h4>
          </div>
        </div>
        <div class="row">
          <div class="content horizontal-end">
            <h3>-Mission duration</h3>
            <h4>668 sols (687 days)</h4>
          </div>
        </div>
        <mars-video></mars-video>
      </div>
    </div>
  </div>
</template>

<script>
  import MarsVideo from '@/components/video'

  export default { 
    name: 'app',
    components: {
      MarsVideo
    }
  }
</script>