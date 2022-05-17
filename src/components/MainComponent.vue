<template>

  <main>
    <div class="container">
      
      <ComicCard  v-for="(comic, index) in dataCard" 
                  :key="`comic${index}`"
                  :comicImg="comic.thumb"
                  :comicTitle="comic.series"
                  :comicPrice="comic.price"
      />
    
    </div>

    <div class="load-more d-flex justify-content-around">
      <a href="#">load more</a>
    </div>

  </main>
  
</template>

<script>

import ComicCard from './ComicCard.vue';
import dataCard from '../assets/data/dataCard'

export default {
  
  name: 'MainComponents',

  components: {ComicCard},

  data(){

    return {
      dataCard
    }
  }
}
</script>

<style lang="scss" scoped>

  @import '../assets/style/vars';

  main {
    background-color: #1C1C1C;
    padding: 20px 0px;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
  }

  a {
    color: #FFFFFF;
    background-color: $primary-color;
    padding: 5px 55px;
  }

</style>