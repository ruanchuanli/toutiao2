<template>
  <div>
    <router-view></router-view>
    <van-tabbar v-model="active">
      <van-tabbar-item icon="home-o" to="/home">
        <template #icon>
          <i class="toutiao toutiao-shouye"></i>
        </template>
        首页</van-tabbar-item
      >
      <van-tabbar-item icon="search" to="/video"
        ><template #icon> <i class="toutiao toutiao-shipin"></i> </template
        >视频</van-tabbar-item
      >
      <van-tabbar-item icon="friends-o" to="/qa"
        ><template #icon> <i class="toutiao toutiao-wenda"></i> </template
        >问答</van-tabbar-item
      >
      <van-tabbar-item icon="setting-o" to="/my"
        ><template #icon> <i class="toutiao toutiao-wode"></i> </template
        >我的</van-tabbar-item
      >
    </van-tabbar>
  </div>
</template>

<script>
export default {
  created () {},
  data () {
    return {}
  },
  methods: {},
  computed: {},
  watch: {},
  filters: {},
  components: {}
}
</script>

<style scoped lang="less">
.toutiao {
  font-size: 40px;
}
/deep/ .van-tabbar-item__text {
  font-size:20px
}
</style>
