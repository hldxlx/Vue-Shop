<template>
    <section>
      <HeaderTop title="我的"></HeaderTop>
      <!-- 利用router-link实现到Login组件的跳转 -->
      <section class="profile-number">
        <router-link :to="'login'">
          <span>登录</span>
        </router-link>
      </section>
    </section>
</template>

<script>
  import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
export default {
  components:{
    HeaderTop
  }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .profile-number
    margin-top 45.5px
</style>
