<template>
  <div class="header">
    <router-link to="/home">首页</router-link>
    <router-link to="/port">港口</router-link>
  </div>
</template>

<script type="text/javascript">
  /******* 第三方 组件库 *****/
  /**** 本地公用变量 公用函数 **/
  /******* 本地 公用组件 *****/
  /**** 当前组件的 子组件等 ***/

  export default {
    name: 'header',
    props: {
      title: {
        type: String,
        default: ''
      }
    },
    data() {
      return {

      }
    },
    components: {}
  }
</script>

<style lang="scss" scoped>
  @import "~assets/css/variable";
  @import "~assets/css/mixin";
</style>
