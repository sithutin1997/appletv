<template>
  <div class="smart-tv">
    <div class="smart-tv__wrapper">

      <div class="smart-tv__about">
        <h2>See it on your smart TV <br>or streaming device.</h2>
        <a href="#">Set up your device ></a>
        <a href="#">Explore compatible devices > </a>
      </div>

      <div class="smart-tv__icon-wrapper">

        <div class="smart-tv__icons">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_samsung__er6s8sp9t126_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_lg__7fxn3l0zf5ua_medium_2x.jpg" alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_vizio__crgnno5ezt2e_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_sony__dv28xq4n91ea_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_xfinity__fohor3dbqrmi_medium_2x.jpg " alt="">
        </div>

        <div class="smart-tv__icons">
          <img src=" https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_roku__d3kr4gpcimoi_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_firetv__f6qpefrj0ree_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_google_tv__e5t4asdc2gsy_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_playstation__djtq2b40wf2a_medium_2x.jpg " alt="">
          <img src="https://www.apple.com/v/apple-tv-plus/ag/images/overview/icon_xbox__cfelmbxxfoaa_medium_2x.jpg " alt="">
        </div>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "SmartTV"
}
</script>

<style lang="scss">
  .smart-tv {
    display: flex;
    justify-content: center;
    .smart-tv__wrapper {
      width: 69%;
      display: flex;
      flex-direction: column;
      .smart-tv__about {
        display: flex;
        flex-direction: column;
        text-align: center;
        h2 {
          font-size: 40px;
          font-weight: 600;
        }
        a {
          margin-top: 13px;
          color: #2997ff;
          text-decoration: none;
          font-weight: 400;
          font-size: 17px;
        }
      }
      .smart-tv__icon-wrapper {
        .smart-tv__icons {
          display: flex;
          justify-content: space-between;
          img {
            width: 117px;
            height: 81px;
          }
        }
      }
    }
  }
</style>