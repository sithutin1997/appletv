<template>
  <div class="nav">
    <div class="nav__list">
      <a>
        <img src="@/assets/icons/apple.svg" alt="" height="44">
      </a>
      <a>
        <span>Store</span>
      </a>
      <a>
        <span>Mac</span>
      </a>
      <a>
        <span>iPad</span>
      </a>
      <a>
        <span>iPhone</span>
      </a>
      <a>
        <span>Watch</span>
      </a>
      <a>
        <span>AirPods</span>
      </a>
      <a>
        <span>TV & Home</span>
      </a>
      <a>
        <span>Only on Apple</span>
      </a>
      <a>
        <span>Accessories</span>
      </a>
      <a>
        <span>Support</span>
      </a>
      <a>
        <img src="@/assets/icons/search.svg" alt="" height="44">
      </a>
      <a><img src="@/assets/icons/cart.svg" alt="" height="44"></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav"
}
</script>

<style lang="scss">
  .nav {
    height: 8%;
    background-color: $secondary;
    display: flex;
    justify-content: center;
    .nav__list {
      width: 69%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      a {
        color: #f5f5f7;
        text-decoration: none;
        font-size: 12px;
        font-weight: 400;
        span {
          font-size: 1em
        }
      }
    }
  }
  
</style>