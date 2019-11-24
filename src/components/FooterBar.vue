<template>
  <van-tabbar v-model="active" class="footer" route >
    <van-tabbar-item icon="home-o" to="/">首页</van-tabbar-item>
    <van-tabbar-item icon="records" to="/category">分类</van-tabbar-item>
    <van-tabbar-item icon="cart-o" to="/cart">购物车</van-tabbar-item>
    <van-tabbar-item icon="contact" to="/profile">我的</van-tabbar-item>
  </van-tabbar>
</template>

<script>
export default {
  data() {
    return {
      active: 0
    };
  },
  // created(){
  //   this.active = localStorage.getItem(parseInt('active'))
  // },
  // methods:{
  //   change(active){
  //     localStorage.setItem('active',active);
  //   }
  // }
};
</script>
<style lang="scss">
.footer {
  height: 1rem;
}
</style>