<template>
  <div class="notify-banner">
    <p>MLS Season Pass. Stream every Major League Soccer match. Coming soon.*</p>
    <a href="#">Notify me ></a>
  </div>
</template>

<script>
export default {
  name: "Notify"
}
</script>

<style lang="scss">
  .notify-banner {
    background-color: $grey;
    display: flex;
    justify-content: center;
    padding: 16px 0;
    line-height: 25px;
    p {
      color: $primary;
    }
    a {
      color: #2997ff;
    }
  }
</style>