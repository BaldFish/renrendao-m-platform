<template>
  <div id="app">
    <div class="main_wrap">
      <router-view class="main" v-if="isRouterAlive"></router-view>
    </div>
    <div class="footer_wrap">
      <ul class="footer">
        <li></li>
      </ul>
    </div>
  </div>
</template>

<script>
  
  export default {
    name: 'App',
    components: {},
    provide() {
      return {
        reload: this.reload
      }
    },
    data() {
      return {
        isRouterAlive: true,
      }
    },
    beforeMount() {
    },
    mounted() {
    },
    beforeUpdate() {
    },
    computed: {
    },
    watch: {
    },
    methods: {
      reload() {
        this.isRouterAlive = false;
        this.$nextTick(() => {
          this.isRouterAlive = true
        })
      },
    }
  }
</script>

<style scoped lang="stylus">
  #app {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    background-color: #ffffff;
    .main_wrap {
      flex: 1;
      box-sizing: border-box;
      margin: 0 auto;
      width 100%
      min-width 640px
    }
    /*.footer_wrap {
      width 100%
      margin 0 auto
      min-width 640px
      position fixed
      bottom 0
      left 0
      background-color #ffffff
      .footer {
        font-size 0
        box-sizing border-box
        border-top solid 1px #e5e5e5; !*no*!
        width 750px
        height 98px
        margin 0 auto
        li {
          margin-top 10px
          display inline-block
          width 33.333%
          text-align center
          font-size 0
          img {
            width 48px
            height 40px
            margin-bottom 10px
          }
          p {
            font-size 28px; !*px*!
            color #333333
          }
        }
        .active {
          p {
            color #5226f3
          }
        }
      }
    }*/
  }
</style>

