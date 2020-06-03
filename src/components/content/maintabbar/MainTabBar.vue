<template>
  <div>
      <tab-bar>
          <tab-bar-item>
              <!-- <img slot="image" src="" alt="">
              <span slot="text" content="首页"></span> -->
          </tab-bar-item>
          <tab-bar-item></tab-bar-item>
          <tab-bar-item></tab-bar-item>
          <tab-bar-item></tab-bar-item>
      </tab-bar>
  </div>
</template>

<script>
import TabBarItem from '../../common/tabbar/TabBarItem'
import TabBar from '../../common/tabbar/TabBar'

export default {
    components: {
        TabBarItem,
        TabBar
    }

}
</script>

<style>

</style>