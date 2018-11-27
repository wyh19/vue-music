<template>
  <div class="recommend" ref="recommend">
    <scroll ref="scroll" class="recommend-content" :data="discList"></scroll>
  </div>
</template>

<script>
import Slider from "base/slider/slider";
import Loading from "base/loading/loading";
import Scroll from "base/scroll/scroll";

export default {
  data() {
    return {
      recommends: [],
      discList: []
    };
  },
  methods: {},
  components: {
    Slider,
    Loading,
    Scroll
  }
};
</script>

<style scoped lang="less">
</style>

