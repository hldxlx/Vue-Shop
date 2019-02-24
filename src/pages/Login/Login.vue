<template>
  <section>
    <div>
      <div>
        <h2>Mint外卖</h2>
        <div>
          <a >短信登录</a>
          <a s>密码登录</a>
        </div>
        <a href="javascript:" class="go_back" @click="$router.back()">
          <i class="iconfont"></i>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        data () {
            return {}
        }
    }
</script>
<style lang="stylus" rel="stylesheet/stylus">
  .go_back
    position absolute
    top 5px
    left 5px
    width 30px
    height 30px
    >.iconfont
      font-size 20px
      color #999
</style>
