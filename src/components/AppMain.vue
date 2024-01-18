<script>
  export default {
    data() {
      return {
        options: [
          {
            img: '../assets/img/buy-comics-digital-comics.png',
            name: "DIGITAL COMICS"
          },
          {
            img: '../assets/img/buy-comics-merchandise.jpg',
            name: "DC MERCHINDISE"
          },
          {
            img: '../assets/img/buy-comics-shop-locator.jpg',
            name: "COMICS SHOP LOCATOR"
          },
          {
            img: '../assets/img/buy-comics-subscriptions.jpg',
            name: "SUBSCRIPTION"
          },
          {
            img: '../assets/img/buy-dc-power-visa.jpg',
            name: "DC POWER VISA"
          },
        ]
        
      }
    },
  }
</script>

<template>

  <div id="main">

    <div class="first-container">
      <h2>
      Content goes here
      </h2>
    </div>

    <div class="second-container">
      <div class="row" v-for="(option, index) in options">
        <div>
          <img :src="option.img" alt="option.img">
        </div>
        <a href="#">
          {{ option.name }}
        </a>
      </div>
    </div>
    
  </div>
  
</template>

<style lang="scss" scoped>

</style>
