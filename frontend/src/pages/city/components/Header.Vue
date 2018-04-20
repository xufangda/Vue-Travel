<template>
  <div class="header">
    <div class="header-title">城市选择</div>
    <router-link to="/">
      <div class="iconfont header-back">&#xe624;</div>
    </router-link>
  </div>
</template>

<script>
export default {
  name: 'city'
}
</script>

<style lang="stylus" scoped>
@import '~styles/variables.styl'
  .header
    position relative
    height $headerHeight
    line-height $headerHeight
    overflow hidden
    text-align center
    color #ffffff
    background $bgColor
    font-size:.32rem
    .header-title
      position absolute
      left:50%
      transform:translate(-50%);
    .header-back
      position absolute
      top 0
      left 0
      width .64rem
      text-align center
      font-size: .4rem
      color #ffffff
</style>
