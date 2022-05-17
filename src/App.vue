<template>
  <div id="app">
    
    <HeaderComponent/>
    <JumbotronComponent/>
    <MainComponent/>
    <ShopComponent/>
    <FooterComponent/>

  </div>
</template>

<script>

import HeaderComponent from './components/HeaderComponent'
import MainComponent from './components/MainComponent'
import ShopComponent from './components/ShopComponent'
import FooterComponent from './components/FooterComponent'
import JumbotronComponent from './components/JumbotronComponent'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumbotronComponent,
    MainComponent,
    ShopComponent,
    FooterComponent
  },

}
</script>

<style lang="scss">

  @import './assets/style/vars';
  @import './assets/style/general';
  @import './assets/style/utils';

</style>
