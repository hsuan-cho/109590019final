<template>
  <div id="nav">
    <router-link to="/">Home</router-link>/
    <router-link to="/one">學士班特色</router-link>/
    <router-link to="/two">學士班簡介</router-link>/
    <router-link to="/three">最新消息</router-link>/
    <router-link to="/four">聯絡</router-link> 
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 0px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #5effff;
}
</style>
