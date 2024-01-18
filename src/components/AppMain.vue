<script>
  export default {
    data() {
      return {
        options: [
          {
            name: "DIGITAL COMICS"
          },
          {
            name: "DIGITAL COMICS"
          },
          {
            name: "DIGITAL COMICS"
          },
          {
            name: "DIGITAL COMICS"
          },
          {
            name: "DIGITAL COMICS"
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
      <div class="row">
        <div class="column" v-for="(option, index) in options">

        </div>
      </div>

    </div>
    
  </div>
  
</template>

<style lang="scss" scoped>

</style>
