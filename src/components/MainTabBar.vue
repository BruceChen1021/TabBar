<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <!-- <img slot="item-icon" src="../assets/img/tabbar/home.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/home_active.svg" alt=""> -->
      <img slot="item-icon" alt="">
      <img slot="item-icon-active" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <!-- <img slot="item-icon" src="../assets/img/tabbar/category.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/category_active.svg" alt=""> -->
      <img slot="item-icon" alt="">
      <img slot="item-icon-active" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="blue">
      <!-- <img slot="item-icon" src="../assets/img/tabbar/cart.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/cart_active.svg" alt=""> -->
      <img slot="item-icon" alt="">
      <img slot="item-icon-active" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="blue">
      <!-- <img slot="item-icon" src="../assets/img/tabbar/profile.svg" alt="">
      <img slot="item-icon-active" src="../assets/img/tabbar/profile_active.svg" alt=""> -->
      <img slot="item-icon" alt="">
      <img slot="item-icon-active" alt="">
      <div slot="item-text">用户</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
import TabBar from './tabbar/TabBar.vue'
import TabBarItem from './tabbar/TabBarItem.vue'

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>

</style>