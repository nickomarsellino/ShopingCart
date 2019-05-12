<template>
  <div id="app">
    <center>
      <div class="stepper">
        <div class="stepper__detail">
          <a class="active round">1</a> Delivery <i class="arrow"></i>
        </div>
        <div class="stepper__detail">
          <a class="unactive round">2</a> Payment <i class="arrow"></i>
        </div>
        <div class="stepper__detail">
          <a class="unactive round">3</a> Finish
        </div>
      </div>
      <div class="cart">
        <div class="back__button">
          <p id="back--arrow">&#8592;&nbsp;&nbsp;&nbsp;</p>
          <p>Back to Cart</p>
        </div>

        <div class="cart__detail">
          <div class="detail--left">
            <h1 id="delivery--title">Delivery Details</h1>
          </div>
          <div class="vl"></div>
          <div class="detail--right">
            <h2 class="summary--data">Summary</h2>
            <p id="summary--items">10 items purchased</p>

            <div class="resultContainer">
              <table class="result__data">
                <tbody>
                <tr>
                  <td class="result--summary">Cost of goods</td>
                  <td class="result--cost">500,000</td>
                </tr>
                <tr>
                  <td class="result--summary">Dropshipping Fee</td>
                  <td class="result--cost">5,900</td>
                </tr>
                <tr>
                  <td class="result--summary"><h2 class="summary--data">Total</h2></td>
                  <td class="result--cost"><h2 class="summary--data">599,999</h2></td>
                </tr>
                </tbody>
              </table>

              <button type="button" class="button__style"><h2>Continue to Payment</h2></button>
            </div>
          </div>
        </div>
      </div>
    </center>
  </div>
</template>

<script>
  export default {
    name: 'app',
    data() {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>


<style src="./App.styl" lang="stylus"></style>


