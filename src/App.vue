<template>
  <div id="App">
    <Tabbar>
      <TabbarItem>
        <img slot="item-icon" src="./assets/img/icon01.png" alt="">
			  <div slot="item-name">首页</div>
      </TabbarItem>
      <TabbarItem>
        <img slot="item-icon" src="./assets/img/icon02.png" alt="">
			  <div slot="item-name">分类</div>
      </TabbarItem>
      <TabbarItem>
        <img slot="item-icon" src="./assets/img/icon03.png" alt="">
			  <div slot="item-name">购物车</div>
      </TabbarItem>
      <TabbarItem>
        <img slot="item-icon" src="./assets/img/icon04.png" alt="">
			  <div slot="item-name">我的</div>
      </TabbarItem>
    </Tabbar>
  </div>
</template>

<script>
import Tabbar from "./components/tabbar/Tabbar.vue"
import TabbarItem from "./components/tabbar/TabbarItem.vue"

export default {
  name: 'App',
  components: {
    Tabbar,
    TabbarItem,
  }
}
</script>

<style>

</style>
