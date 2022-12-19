<template>
  <div class="container">
    <Nav />
    <TitleNav />
    <Notify />
    <Hero />
    <div class="plan-section">
      <AboutPlan />
      <Plans />
    </div>
    <div class="tv-section">
      <AppleDevices />
      <SmartTV />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style lang="scss">
  .container {
    overflow-x: hidden;
    .plan-section {
      background-color: $secondary;
    }
    .tv-section {
      padding-bottom: 150px;
    }
  }
</style>