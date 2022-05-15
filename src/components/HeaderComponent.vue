<template>

  <header>
    <div class="container d-flex justify-content-between align-items-center">
      <img src="../assets/img/dc-logo.png" alt="">

      <nav>
        <ul class="d-flex">

          <li :class="{'active' : menu.isActive}" v-for="(menu, index) in HeaderMenu" :key="`menu-${index}`">
            <a :href="menu.href">{{menu.name}}</a>
          </li>

        </ul>
      </nav>

    </div>
  </header>
  
</template>

<script>

export default {
  name:'HeaderComponent',

  data() {
    return {
      HeaderMenu: [
        {
          name: 'characters',
          href: '#',
          isActive: false
        },
        
        {
          name: 'comics',
          href: '#',
          isActive: true
        },

        {
          name: 'movies',
          href: '#',
          isActive: false
        },

        {
          name: 'tv',
          href: '#',
          isActive: false
        },

        {
          name: 'games',
          href: '#',
          isActive: false
        },

        {
          name: 'collectibles',
          href: '#',
          isActive: false
        },

        {
          name: 'videos',
          href: '#',
          isActive: false
        },

        {
          name: 'fans',
          href: '#',
          isActive: false
        },

        {
          name: 'news',
          href: '#',
          isActive: false
        },

        {
          name: 'shop',
          href: '#',
          isActive: false
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

  @import '../assets/style/vars';

  header {
    margin: 20px 0;
  }

  a {
    padding: 0px 10px ;
    color: #334B5F;

    &:hover {
    color: $primary-color
    }
  } 

  .active {
    border-bottom: 5px solid $primary-color;
  }
  
</style>