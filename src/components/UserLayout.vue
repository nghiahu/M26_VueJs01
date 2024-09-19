<template>
  <div class="main-layout">
    <header-component></header-component>
    <navigation-component></navigation-component>
    <div class="content">
      <menu-component></menu-component>
        <div class="cart-container">
          <cart-component v-for="n in 9" :key="n"></cart-component>
        </div>
        <article-component></article-component>
        
    </div>
  </div>
</template>

<script setup>
import HeaderComponent from './layoutBt8/HeaderComponent.vue';
import NavigationComponent from './layoutBt8/NavigationComponent.vue';
import MenuComponent from './layoutBt8/MenuComponent.vue';
import ArticleComponent from './layoutBt8/ArticleComponent.vue';
import CartComponent from './layoutBt8/CartComponent.vue';
</script>

<style scoped>
.content {
  display: flex;
  width: 600px;
}
.main-content {
  flex-grow: 1;
}
.cart-container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}
</style>
