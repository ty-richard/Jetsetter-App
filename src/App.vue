<template>
  <div id="app">
    <header>
      <img src="http://locatravel.am/images/about_us_icon.png" class="logo" width="50px" height="50px" alt="">
      <a href="#/home" style="color:white"><span>Jetsetters</span></a>
    </header>
    <main>
      <img src="http://locatravel.am/images/about_us_icon.png"width="290px" height="250px" alt="">
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
main {
  text-align: center;
  margin-top: 41px;
}
header {
  margin: 0;
  height: 60px;
  padding: 0 16px 0 24px;
  background-color: #0082c1;
  color: #ffffff;
}
.logo {
  float: left;
}
header span {
  display: block;
  position: relative;
  font-size: 20px;
  line-height: 1;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-top: 16px;
  padding-left: 55px;
}
</style>
