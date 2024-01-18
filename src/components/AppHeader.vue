<script>
  export default {
    data() {
      return {
        linksHeader: [
          {
            link: 'CHARACTERS'
          },
          {
            link: 'COMICS'
          },
          {
            link: 'MOVIES'
          },
          {
            link: 'TV'
          },
          {
            link: 'GAMES'
          },
          {
            link: 'COLLECTIBLES'
          },
          {
            link: 'VIDEOS'
          },
          {
            link: 'FANS'
          },
          {
            link: 'NEWS'
          },
          {
            link: 'SHOP'
          },

        ]
      }
    },
  }
</script>

<template>

  <div id="header">

    <div>
      <img src="../assets/img/dc-logo.png" alt="">
    </div>

    <div>
      <ul>
        <li v-for="(singleLinkHeader, index) in linksHeader">
          <a href="#"> {{ singleLinkHeader.link }}</a>
        </li>
      </ul>
    </div>

  </div>
  
</template>

<style scoped>

</style>
