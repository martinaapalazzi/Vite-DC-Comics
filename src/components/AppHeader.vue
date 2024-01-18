<script>
import logo from '../assets/img/dc-logo.png';
  export default {
    data() {
      return {
        logo,
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

    <div class="header-container">

      <div class="logo-container">
        <img :src="logo" alt="Logo">
      </div>

      <div>
      
        <ul>
          <li v-for="(singleLinkHeader, index) in linksHeader">
            <a href="#"> {{ singleLinkHeader.link }}</a>
          </li>
        </ul>

      </div>


    </div>

  </div>
  
</template>

<style lang="scss" scoped>

</style>
