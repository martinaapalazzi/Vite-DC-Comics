<script>
  export default {
    data() {
      return {
        options: [
          {
            img: './src/assets/img/buy-comics-digital-comics.png',
            name: "DIGITAL COMICS"
          },
          {
            img: './src/assets/img/buy-comics-merchandise.png',
            name: "DC MERCHINDISE"
          },
          {
            img: './src/assets/img/buy-comics-shop-locator.png',
            name: "COMICS SHOP LOCATOR"
          },
          {
            img: './src/assets/img/buy-comics-subscriptions.png',
            name: "SUBSCRIPTION"
          },
          {
            img: './src/assets/img/buy-comics-subscriptions.png',
            name: "DC POWER VISA"
          },
        ]
        
      }
    },
  }
</script>

<template>

  <div id="main">

    <div class="container">

      <div>
        <h2 class="content-container">
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
    
  </div>
  
</template>

<style lang="scss" scoped>

</style>
