<template>
  <div class="home">
    <div class="home_top">
      <div class="img_box">
        <img src="./images/home_top.png" alt="">
      </div>
    </div>
    <div class="home_body">
      <div class="code">
        <div class="android">
          <img src="./images/Android.png" alt="">
          <p>Android版人人道</p>
        </div>
        <div class="gongzhonghao">
          <img src="./images/gongzhonghao.png" alt="">
          <p>人人道公众号</p>
        </div>
      </div>
      <div class="about" >
        <h3><img src="./images/about.png" alt=""></h3>
        <ul class="text">
          <li>
            <span>人人道，是为车之道</span>。背靠汽车后龙头平台，近30年市场深耕，集数据、技术、品牌口碑为一身，利用全新技术构建商业新生态。
          </li>
          <li>
            <span>人人道，是为DAO之道</span>。DAO即基于共识之分布式自治组织。未来商业必将走向无数DAO组织，未来商业之世界大同趋势下，须践行为DAO之道，方得始终。
          </li>
          <li>
            <span>人人道，是为人之道</span>。“区块链”三字，荣耀与争议并存。有兢业向上之精诚技术，亦不乏扰乱风气之浊流。人人道虽为链圈新势力，但志存正道、匡正链圈风气之理想；我们深信，欲行大事、成大业，须固正为人之道。
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "home",
    components: {},
    data() {
      return {}
    },
    created() {
    },
    mounted() {
    },
    watch: {},
    computed: {},
    methods: {},
  }
</script>

<style scoped lang="stylus">
  .home {
    width 750px
    margin 0 auto
    
    .home_top {
      .img_box {
        margin 0 auto
        text-align center
        
        img {
          width 750px
          height 400px
        }
      }
    }
    
    .home_body {
      position relative
      
      .code {
        box-sizing border-box
        margin 0 auto
        width: 650px;
        height: 350px;
        background-color: #ffffff;
        box-shadow: -5px 1px 26px 1px rgba(0, 0, 0, 0.11);
        border-radius: 50px;
        border: solid 1px #eeeeee; /*no*/
        font-size 0
        text-align center
        position absolute
        top -116px
        left 50px
        
        .android, .gongzhonghao {
          display inline-block
          font-size: 24px; /*px*/
          color: #333333;
          margin-top 70px
          
          img {
            width 182px
            height 182px
          }
          
          p {
            margin-top 24px;
          }
        }
        
        .android {
          margin-right 130px
        }
      }
      .about{
        padding-top 310px
        h3{
          text-align center
          font-size 0
        }
        .text{
          box-sizing border-box
          margin 0 auto
          padding 20px
          width: 685px;
          height: 482px;
          background-color: #ffffff;
          box-shadow: -5px 1px 26px 1px rgba(0, 0, 0, 0.11);
          border-radius: 50px;
          border: solid 1px #eeeeee;/*no*/
          li{
            color #333333
            line-height 36px;
            font-size 22px;/*px*/
            span{
              font-size 30px;/*px*/
            }
          }
        }
      }
    }
  }
</style>
