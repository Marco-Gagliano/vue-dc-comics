<template>

  <div class="shop d-flex align-items-center">
    <div class="container">

      <nav>
        <ul class="d-flex">

          <li>
            <a href="#">
              <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics Link">
              digital comics
            </a>
          </li>

          <li>
            <a href="#">
              <img src="../assets/img/buy-comics-merchandise.png" alt="DC Merchandise Link">
              dc merchandise
            </a>
          </li>

          <li>
            <a href="#">
              <img src="../assets/img/buy-comics-subscriptions.png" alt=" Subscription Link">
              subscription
            </a>
          </li>

          <li>
            <a href="#">
              <img class="locator" src="../assets/img/buy-comics-shop-locator.png" alt="Comics Shop Locator Link">
              comic shop locator
            </a>
          </li>

          <li>
            <a href="#">
              <img class="power-visa" src="../assets/img/buy-dc-power-visa.svg" alt="DC Power Visa Link">
              dc power visa 
            </a>
          </li>

        </ul>
      </nav>

    </div>
  </div>
  
</template>

<script>
export default {
  name: 'ShopComponent'
}
</script>

<style lang="scss" scoped>

  @import '../assets/style/vars';

  .shop {
    background-color: $primary-color;
    height: 200px;
  }

  img {
    width: 25%;
  }

  li {
    padding: 0px 10px ;

    a {
      color: #FFFFFF;

      img {
        margin-right: 10px;
      }
    }
  } 
  
  .power-visa {
    width: 19%;
  }

  .locator {
    width: 17%;
  }

</style>