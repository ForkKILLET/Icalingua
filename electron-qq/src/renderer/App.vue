<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "app",
};
</script>

<style>
@import url("./assets/stylesheet.css");

@font-face {
  font-family: "msyh";
  src: url("./assets/msyh.ttf");
}
@font-face {
  font-family: "twemoji";
  src: url("./assets/Twemoji.ttf");
}

html,
body {
  /*height: 100%;*/
  width: 100%;
  margin: 0;
  color: #303133;
}

* {
  font-family: font, "CircularSpotifyTxT Book Web", msyh, twemoji, "PingFang SC", sans-serif;
}

:focus {
  outline: none;
}

div#app {
  -webkit-user-select: none;
}
</style>
