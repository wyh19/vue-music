<template>
  <div id="app">
    <m-header></m-header>
    <keep-alive>
       <router-view/>
    </keep-alive>
   
  </div>
</template>

<script>
import MHeader from 'components/m-header/m-header'
export default {
  components:{
    MHeader
  }
}
</script>

<style scoped lang="less" rel="stylesheet/less">
</style>
