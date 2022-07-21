<template>
     <tab-bar>
      <tab-bar-item path="/home" activecolor="deeppink">
        <img slot="item-icon" src="../../../assets/img/tabbar/icon-首页.png" alt="">
        <img slot="item-icon-active" src="../../../assets/img/tabbar/icon-首页active.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activecolor="deeppink">
         <img slot="item-icon" src="../../../assets/img/tabbar/icon-应用.png" alt="">
         <img slot="item-icon-active" src="../../../assets/img/tabbar/icon-应用active.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activecolor="deeppink">
        <img slot="item-icon" src="../../../assets/img/tabbar/icon-钱包.png" alt="">
        <img slot="item-icon-active" src="../../../assets/img/tabbar/icon-钱包active.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activecolor="deeppink">
         <img slot="item-icon" src="~assets/img/tabbar/icon-账号.png" alt="">
         <img slot="item-icon-active" src="~assets/img/tabbar/icon-账号active.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
import TabBar from '../../common/tabbar/TabBar.vue'
import TabBarItem from '../../common/tabbar/TabBarItem.vue'

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
