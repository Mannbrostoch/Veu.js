<template>
<div class="dashboard">
<div class="wapper-header">
  <div class="header-container">
    <div class="header-logo">
      <img src="../assets/logo.png" alt="logo">
    </div>
    <div class="header-nav">
      <span>首页</span>
      <span>关于我们</span>
      <span>产品中心</span>
      <span>新闻中心</span>
      <span>联系我们</span> 
    </div>  
  </div>
</div>

<!-- <div class="sidebar">
  <div class="sidebar-container">
    <div class="sidebar-nav">
      <span>首页</span>
      <span>关于我们</span>
      <span>产品中心</span>
      <span>新闻中心</span>
      <span>联系我们</span>
     
    </div>
  </div>
</div> -->
</div>
</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.dashboard{
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}

.wapper-header{
  width: 100%;
  height: 80px;
  background-color: #fff;
  box-shadow: 0 0 10px #ccc;
}
.header-container{
  width: 1200px;
  height: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header-logo{
  width: 200px;
  height: 100%;
}
.header-logo img{
  width: 100%;
  height: 100%;
} 
.header-nav{
  width: 800px;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header-nav span{
  font-size: 16px;
  color: #333;
  cursor: pointer;
}

.sidebar{
  width: 100%;
  height: 100%;
  background-color: #fff;
  box-shadow: 0 0 10px #ccc;
}
.sidebar-container{
  width: 1200px;
  height: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.sidebar-nav{
  width: 800px;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

</style>
