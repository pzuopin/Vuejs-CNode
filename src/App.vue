<template>
  <div id="app">
      <cnode-header></cnode-header>
      <cnode-nav></cnode-nav>
      <router-view></router-view>
  </div>
</template>

<script>
import CnodeHeader from './components/CnodeHeader'
import CnodeNav from './components/CnodeNav.vue'
export default {
  data(){
    return {

    }
  },
  components:{
    CnodeHeader,
    CnodeNav
  }
}
</script>

<style lang="stylus">
@import './assets/common.styl'
</style>
