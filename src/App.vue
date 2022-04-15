<template>
  <div id="App">
    <Tabbar>
      <TabbarItem>
        <!-- #是插槽的语法糖格式 -->
        <template #item-icon>
          <img src="./assets/img/icon01.png" alt="">
        </template>
        <template #item-name>
          <div>首页</div>
        </template>
      </TabbarItem>
      <TabbarItem>
        <template v-slot:item-icon>
          <img src="./assets/img/icon02.png" alt="">
        </template>
        <template v-slot:item-name>
          <div>分类</div>
        </template>
      </TabbarItem>
      <TabbarItem>
        <template v-slot:item-icon>
          <img src="./assets/img/icon03.png" alt="">
        </template>
        <template v-slot:item-name>
          <div>购物车</div>
        </template>
      </TabbarItem>
      <TabbarItem>
        <template v-slot:item-icon>
          <img src="./assets/img/icon04.png" alt="">
        </template>
        <template v-slot:item-name>
          <div>我的</div>
        </template>
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
