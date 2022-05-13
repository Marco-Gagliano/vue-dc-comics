<template>

  <header>
    <div class="container d-flex justify-content-between align-items-center">
      <img src="../assets/img/dc-logo.png" alt="">
      <nav>
        <ul class="d-flex">
          <li>
            <a href="#">characters</a>
          </li>

          <li class="active">
            <a href="#">comics</a>
          </li>

          <li>
            <a href="#">movies</a>
          </li>

          <li>
            <a href="#">tv</a>
          </li>

          <li>
            <a href="#">games</a>
          </li>

          <li>
            <a href="#">collectibles</a>
          </li>

          <li>
            <a href="#">videos</a>
          </li>

          <li>
            <a href="#">fans</a>
          </li>

          <li>
            <a href="#">news</a>
          </li>

          <li>
            <a href="#">shop</a>
          </li>

        </ul>
      </nav>

    </div>
  </header>
  
</template>

<script>
export default {

  name:'HeaderComponent'
}
</script>

<style lang="scss" scoped>

  header {
    
    margin: 20px 0;
  }

  ul {
    list-style: none;

    li {
      padding: 0px 10px ;

      a {
        text-decoration: none;
        color: #334B5F;
        &:hover {
        color: #0282F9}
      } 
    }
  }

  .active {
    border-bottom: 2px solid #0282F9;
  }
  

</style>