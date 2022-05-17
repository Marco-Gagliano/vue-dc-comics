<template>

  <div class="sc-card">

    <div>
      <img :src="comicImg" alt="comicTitle">
    </div>
    
    <p>{{comicTitle}}</p>
    <p>{{comicPrice}}</p>

  </div>
          
</template>

<script>
export default {

  name: 'ComicCard',
  
  props:{
    comicTitle: String,
    comicPrice: String,
    comicImg: String
  }
}
</script>

<style lang="scss" scoped>

  .sc-card {
    flex-basis: calc(100% / 6);
  }

  img {
    padding: 30px 18px 0px 0px;
  }

  h4, p {
    color: #FFFFFF;
    margin-top: 20px
  }

</style>