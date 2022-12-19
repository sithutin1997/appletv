<template>
  <div class="title-nav">
    <div class="title-nav__wrap">
      <h2>Apple TV +</h2>
      <button>Stream Now</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TitleNav'
}
</script>

<style lang="scss">
  .title-nav {
    position: sticky;
    top: 10px;
    background-color: $grey;
    display: flex;
    justify-content: center;
    .title-nav__wrap {
      display: flex;
      width: 69%;
      justify-content: space-between;
      h2 {
        color: $primary;
        font-size: 21px;
        font-weight: 600;
        margin: 14px 0;
      }
      button {
        background-color: $primary;
        margin: 14px 0;
        border-radius: 980px;
        padding: 4px 11px;
        font-size: 12px;
      }
    }
    
  }
</style>