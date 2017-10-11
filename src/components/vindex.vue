<template>
  <div class="vindex">
  <div class="title">
    <img style='vertical-align:middle'src="../assets/logo-2.jpg"  alt="Readhub">
    <div class="nav">
      <router-link to="/" style="text-decoration:none">同袍原创</router-link>
      <router-link to="/TmtNews" style="text-decoration:none">军事新闻</router-link>
      <router-link to="/DeveloperInfo" style="text-decoration:none">其他热点</router-link>
      <router-link to="/">同袍原创</router-link>
      <router-link to="/TmtNews">军事新闻</router-link>
      <router-link to="/DeveloperInfo">其他热点</router-link>
    </div>
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
  .title{
    word-spacing: 1em;
    text-align:justify;
  }
 .nav{
   margin:0 auto;border:1px solid #fff;width:80%;height:200%;
   word-break:  keep-all;
   display:inline-block;
   vertical-align:middle;
   font-family: "黑体",黑体,Times New Roman;
   }

 .line{
   margin:1em 0em auto;;width: inherit;heigh:inherit;
   border:0.01em solid #cfcfcf;
 }
  .nav a{
    font-family: "新宋体",黑体,Times New Roman;
    text-decoraction:none
  }
  a.router-link-exact-active{
    font-weight: bold;
  }
</style>

