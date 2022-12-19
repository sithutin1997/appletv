<template>
  <div class="subscription-plans">
    <div class="subscription-plans__types">

      <div class="subscription-plans__type1">
        <h2>Buy an Apple Device</h2>
        <h3>3 months free.</h3>
        <p>Apple TV+ is included for 3 months
          when you purchase an Apple
          device and redeem the offer
          within 90 days.<sup>1</sup>
        </p>
        <button>Check eligibility</button>
      </div>

      <div class="subscription-plans__type2">
        <h2>Free 7-day trial</h2>
        <h3>$6.99/mo.</h3>
        <p>A monthly subscription is just $6.99 per month
          after a free 7-day trial.
          Share Apple TV+ with your family.<sup>2</sup>
        </p>
        <button>Try it free</button>
      </div>

      <div class="subscription-plans__type3">
        <h2>Free 1-month trial</h2>
        <h3>Apple One</h3>
        <p>Bundle Apple TV+ with up to five other great 
          services for one low monthly price. 
          And enjoy more for less. 
          <a href="#">Learn more ></a>
        </p>
        <button>Try Apple One free<sup>3</sup></button>
      </div>

    </div>
  </div>
  
</template>

<script>
export default {
  name: 'Plans'
}
</script>

<style lang="scss">
  .subscription-plans {
    display: flex;
    justify-content: center;
    .subscription-plans__types {
      display: flex;
      justify-content: space-between;
      width: 69%;
      .subscription-plans__type1, .subscription-plans__type2, .subscription-plans__type3 {
        width: 28%;
        h2,h3,p {
          color: $primary;
        }
        h2 {
          font-size: 19px;
          font-weight: 600;
          line-height: 23px;
        }
        h3 {
          margin-top: 12px;
          font-size: 28px;
          font-weight: 700;
        }
        p {
          margin: 5px 0 23px;
          font-size: 17px;
          font-weight: 400;
        }
        button {
          border-radius: 980px;
          padding: 12px 22px;
          background-color: $primary;
        }
      }
    }
  }
</style>