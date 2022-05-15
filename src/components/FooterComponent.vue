<template>

  <footer>

    <div class="container-fluid">

      <div class="contacts">

        <div class="container logo d-flex justify-content-between">

          <div class="contact-list d-flex">

            <div class="contact-dc-comics">
              
              <h4>dc comics</h4>

              <ul>
                <li><a href="#">characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li><a href="#">videos</a></li>
                <li><a href="#">news</a></li>
              </ul>

              <h4>shop</h4>

              <ul>
                <li><a href="#">shop dc</a></li>
                <li><a href="#">shop dc collectibles</a></li>
              </ul>

            </div>

            <div class="contact-dc">

              <h4>dc</h4>

              <ul>
                <li><a href="#">terms of use</a></li>
                <li><a href="#">privacy policy (new)</a></li>
                <li><a href="#">ad choices</a></li>
                <li><a href="#">advertising</a></li>
                <li><a href="#">jobs</a></li>
                <li><a href="#">subscription</a></li>
                <li><a href="#">talent workshops</a></li>
                <li><a href="#">cpsc certificates</a></li>
                <li><a href="#">ratings</a></li>
                <li><a href="#">shop help</a></li>
                <li><a href="#">contact us</a></li>
              </ul>

            </div>

            <div class="contact-sites">

              <h4>sites</h4>

              <ul>
                <li><a href="#">dc</a></li>
                <li><a href="#">mad magazine</a></li>
                <li><a href="#">dc kids</a></li>
                <li><a href="#">dc universe</a></li>
                <li><a href="#">dc power visa</a></li>
              </ul>

            </div>

          </div>

          <div class="dc-logo">
            <img src="" alt="">
          </div>

        </div>

        <div class="contact-social">
          <div class="container d-flex justify-content-between">

            <button class="sign-up">sign-up now!</button>

            <div class="social-media d-flex align-items-center">

              <a class="follow" href="#">follow us</a>

              <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="">
              </a>

              <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="">
              </a>

            </div>

          </div>
        </div>

      </div>

    </div>

  </footer>
  
</template>

<script>
export default {
  name: 'FooterComponent'
}
</script>

<style lang="scss" scoped>

  @import '../assets/style/vars';

  footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    display: flex;
    justify-content: space-between;
  }

  .container-fluid {
    padding: 0;
  }

  .logo{
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position: right
  }

  h4 {
    color: #FFFFFF
  }

  ul {
    padding: 0;
  }

  li {
    padding: 0px 0px ;
  }

  a {
    color: #858585;
  }

  .contact-dc-comics,
  .contact-dc,
  .contact-sites {
    margin: 30px 15px 0px 0px;
  }

  .contact-social {
    background-color: #303030;
  }

  .sign-up {
    margin: 25px 0px;
    color: #FFFFFF;
    background-color: #303030;
    border: 2px solid $primary-color;
    font-size: 20px;
    padding: 10px 20px
  }

  .social-media a{
    margin-left: 18px;

  }

  .follow {
    font-size: 22px;
    color: $primary-color
  }
  // .social 
  //   height: 100px;
  //   background-color: chocolate;
  // 

</style>
