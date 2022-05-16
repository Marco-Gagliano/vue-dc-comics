<template>

    <div class="jumbotron container-fluid">
      <div class="container">

        <span>current series</span>

      </div>
    </div>

</template>

<script>
export default {
  name: 'JumbotronComponents'
}
</script>

<style lang="scss" scoped>

  @import '../assets/style/vars';

  .jumbotron {
    background-image: url(../assets/img/jumbotron.jpg);
    height: 400px;
    position: relative;
  }

  span {
    background: $primary-color;
    color: #FFFFFF;
    font-size: 30px;
    padding: 5px 20px;
    position: absolute;
    bottom: -6%;
    left: 22%;
  }

</style>