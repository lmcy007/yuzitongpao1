<template>
  <div class="vindex">
    <img src="../assets/2.png" alt="Readhub">
    <div class="nav">
      <router-link to="/">热门话题</router-link>
      <router-link to="/TmtNews">TMT新闻</router-link>
      <router-link to="/DeveloperInfo">开发者资讯</router-link>
    </div>
    <div class="line"></div>
    <backTop></backTop>
    <router-view></router-view>
  </div>

</template>

<script>
  import backTop from '../components/BackTop'
  export default {
    name: 'vindex',
    components: {
      backTop
    }
  }
</script>
<style scoped>
  .vindex{
    font-family: "楷体",黑体,Times New Roman;
    margin: 1% 0% 0% 1%;

     }
 .nav{
   margin:0 auto;border:1px solid #fff;width:80%;height:200%;
   word-break:  keep-all;
   display:inline-block;
   text-align:justify;
   }

 .line{
   margin:0,auto;width:inherit;heigh:1%;
   border: 0.1em solid #f00;

 }
  .nav a{
    font-family: "宋体",黑体,Times New Roman;
    line-height:3em;
  }
</style>

