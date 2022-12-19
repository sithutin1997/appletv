<template>
  <div class="plans">
    <div class="plans__about-plan">
      <h2>New Apple Originals every month.</h2>

      <div class="plans__devices">  
        <h2>Stream on the Apple TV app on Apple</h2>
        <h2>devices,smart TVs, consoles, or sticks.</h2>
      </div>

      <h2>Share Apple TV+ with your family.</h2>
    </div>
  </div>
 
  
</template>

<script>
export default {
  name: 'AboutPlan'
}
</script>

<style lang="scss">
  .plans {
    display: flex;
    justify-content: center;
    padding-bottom: 150px;
    .plans__about-plan {
      width: 69%; 
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      gap: 50px;
      h2 {
        color: $primary;
        font-size: 40px;
        font-weight: 700;
        .plans__devices {
          h2 {
            color: $primary;
            font-size: 40px;
            font-weight: 700;
          }
        }
      }
    }
  }
  
</style>