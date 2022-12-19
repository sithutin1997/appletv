<template>
  <div class="devices">
    <div class="devices__wrapper"> 
      <div class="devices__about">
        <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/apple_tv_app_icon__cth1s5qlqpyu_medium_2x.png" width="76" height="76" alt="">
        <h2>Watch Apple TV+ anywhere</h2>
        <h2>on the Apple TV app.</h2>
        <p>Find the Apple TV app on your favorite Apple devices.
          <br>
          Or watch Apple TV+ online at <a href="">tv.apple.com</a>.
        </p>
      </div>
      <div class="devices__icon-wrapper">

        <div class="devices__icon">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_apple_tv__r2nel0gcigam_medium_2x.jpg" alt="">
          <p>Apple TV</p>  
        </div>

        <div class="devices__icon">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_iphone__c914mkstye0y_medium_2x.jpg " alt="">
          <p>iPhone</p>  
        </div>

        <div class="devices__icon">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_ipad__cyk6qow5fiqa_medium_2x.jpg" alt="">
          <p>iPad</p>  
        </div>

        <div class="devices__icon">
        <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_mac__b7y797p7oouq_medium_2x.jpg" alt="">
          <p>Mac</p>  
        </div>
        <div class="devices__icon">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_airplay__ddkvcm0sxtm6_medium_2x.jpg" alt="">
          <p>AirPlay</p>  
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppleDevices"
}
</script>

<style lang="scss">
  .devices {
    width: 100%;
    display: flex;
    justify-content: center;
    .devices__wrapper {
      display: flex;
      width: 69%;
      flex-direction: column;
      justify-content: space-between;
      .devices__about {
       text-align: center;
       padding: 130px 0 52px;
       img {
        margin-bottom: 17px;
       }
       h2 {
        font-size: 72px;
        font-weight: 700;
       }
       p {
        margin: 20px 0;
        a {
          color: blue;
        }
       }
      }
      .devices__icon-wrapper {
        display: flex;
        justify-content: space-between;
        margin-bottom: 67px;
        .devices__icon {
          p {
            text-align: center;
            margin-top: 17px;
            font-size: 19px;
            font-weight: 600;
          }
        }
      }
    }
  }
</style>