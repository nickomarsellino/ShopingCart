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
          <p id="back--arrow">&#8592;&nbsp;&nbsp;&nbsp;</p><p>Back to Cart</p>
        </div>

        <div class="cart__detail">
            <div class="detail--left">
                <h2>KIIRI</h2>
            </div>
            <div class="detail--right">
                <h2>KANAN</h2>
            </div>
        </div>

        <div class="cart__delivery">
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


