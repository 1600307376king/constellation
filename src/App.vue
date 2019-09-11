<template>
  <div id="app">

    <div class="header_top"></div>
    <div class="header_top_left"></div>
    <div class="header_top_right"></div>
    <div class="header">
      <div class="title">
        <h1>寻找有缘人</h1>

      </div>
      <div class="image_logo">
        <img src="./assets/top_logo.jpg" style="height: 92px">
      </div>
    </div>
    <div class="top_line"></div>
    <div class="all">
      <div class="middle">
        <div class="image"></div>
        <InputParameter></InputParameter>
<!--        <div class="footer">尾部</div>-->
      </div>
    </div>


  </div>
</template>

<script>
import InputParameter from "@/views/InputParameter";
import 'bootstrap/dist/css/bootstrap-grid.min.css'
import 'bootstrap/dist/js/bootstrap.min'
export default {
  name: 'app',
  components: {
    // eslint-disable-next-line vue/no-unused-components
      InputParameter
  }
}
</script>

<style lang="scss">
@import "./base.scss";
* {
  margin: 0;
  padding: 0;
  list-style: none;
}
html, body {
  background: white;
}
.header_top {
  background: #FF6699;
  width: 100%;
  height: 10px;
}
.header{
  background: white;
  width: 1000px;
  height: 100px;
  margin: 0 auto;

  .title {
    width: 69%;
    text-align: left;
    float: left;
    padding: 25px;
    position: relative;
  }
  .image_logo {
    width: 29%;
    height: 92px;
    float: right;
    text-align: right;
    position: relative;
  }
}
.top_line {
  width: 100%;
  height: 2px;
  background: #EEEEEE;
}
.middle {
  width: 1000px;
  height: 1500px;
  text-align: center;
  background: antiquewhite;
  margin: 0 auto;
  .image {
    height: 100px;
    width: 100%;
    background: #FF6699;
  }


  .footer {
    background: lightblue;
    width: 100%;
    height: 100px;
    margin: 0 auto;
    bottom: 1px;
  }
}
</style>
