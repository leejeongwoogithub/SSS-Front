<template>
  <nav>
    <v-app-bar class="flex-grow-0" color="white" elevation="0" style="display: flex; justify-content: center;">
      <ul class="menu mt-5">
          <li>
            <router-link :to="{ name: 'IntroductionPage' }">Introduction</router-link>
          </li>
          <li>
            <router-link :to="{ name: 'IngredientListPage' }">Self Salad</router-link>
          </li>
          <li>
            <router-link :to="{ name: 'ProductListPage' }">Salad</router-link>
          </li>
          <li>
            <router-link :to="{ name: 'SideProductListPage' }">Side</router-link>
          </li>
          <li>
            <router-link :to="{ name: 'QnaBoardListPage' }">Community</router-link>
          </li>
        </ul>
      </v-app-bar>
  </nav>
</template>

<script>
export default {
}
</script>

<style scoped>
  ul.menu li{ display: inline;}
  .menu a:hover {
    color: #3d7e27 !important;
  }
  .menu a {
    color: black;
    font-weight: 600;
    margin-right: 80px;
    transition: all 0.3s ease 0s;
  }
a {
    text-decoration: none;
  }


</style>