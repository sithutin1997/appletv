<template>
  <div class="hero">
    <video autoplay muted loop id="myVideo">
      <source src="../assets/videos/appletv-hero-video-large.mp4" type="video/mp4">
    </video>
    <div class="content">
      <div class="content__header">
        <h1>All Apple Originals.</h1>
        <h1>Only on Apple TV +.</h1>
      </div>
      <button>Stream Now</button>
      <div class="content__watch">
        <p>Watch on the</p>
        <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_tv_app_icon__cth1s5qlqpyu_medium_2x.png" width="41" height="41"/>
        <p>app</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero"
}
</script>

<style lang="scss">
.hero {
  position: relative;
  display: flex;
  justify-content: center;
  .content {
    position: absolute;
    display: flex;
    flex-direction: column;
    height: 50%;
    top: 25%;
    width: 69%;
    padding: 15px;
    gap: 25px;
    .content__header {
      h1 {
        font-size: 72px;
        color: $primary;
      }  
    }
    button {
      margin: 14px 0;
      border-radius: 980px;
      padding: 18px 31px;
      font-size: 17px;
      width: 20%;
    }
    .content__watch {
      display: flex;
      align-items: center;
      color: $primary;
      p {
        margin: 0 10px;
      }
    }
  }
}
  
</style>