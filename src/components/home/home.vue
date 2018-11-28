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
      <div class="about explain" >
        <h3><img src="./images/explain.png" alt=""></h3>
        <p>人人道，全球首款集结积分、资产、身份为一体的基于区块链技
          术的新型移动端应用。</p>
        <ul class="text">
          <li>
            <i></i><span>在这里，您可以一键免费生成您的区块链车证及身份证，生成即可赚钱；</span>
          </li>
          <li>
            <i></i><span>在这里，您是手中数据唯一的主权所有者，一旦上链，尊享永久收益权；</span>
          </li>
          <li>
            <i></i><span>在这里，倚靠区块链技术，将带您进入一个前所未有的新世界。</span>
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
        padding-bottom 68px
        h3{
          text-align center
          font-size 0
          margin-bottom 43px
        }
        .text{
          box-sizing border-box
          margin 0 auto
          padding 40px 50px
          width: 685px;
          //height: 482px;
          background-color: #ffffff;
          box-shadow: -5px 1px 26px 1px rgba(0, 0, 0, 0.11);
          border-radius: 50px;
          border: solid 1px #eeeeee;/*no*/
          li{
            font-family: SourceHanSansCN-Regular;
            color #333333
            line-height 46px;
            font-size 22px;/*px*/
            span{
              font-family: SourceHanSansCN-Medium;
              font-size 30px;/*px*/
            }
          }
        }
      }
      .explain{
        padding-top 0
        h3{
          margin-bottom 20px
        }
        p{
          width 685px
          margin 0 auto
          text-align center
          font-size: 24px;
          color: #222222;
          line-height 32px
          margin-bottom 40px
        }
        .text{
          li{
            font-size 0
            i{
              display inline-block
              background-color: #5226f3;
              width 16px
              height 16px
              border-radius 50%
              vertical-align top
              margin-top 8px
              margin-right 18px
            }
            span{
              display inline-block
              width 524px
              font-size 22px;/*px*/
              line-height 30px
              font-family: SourceHanSansCN-Regular;
            }
          }
        }
      }
    }
  }
</style>
