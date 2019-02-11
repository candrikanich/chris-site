<template>
  <div id="app" class="grid-container">
    <router-view/>
  </div>
</template>

<style lang="less">
  @import url("assets/styles/main.less");

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: @alternate-background-color;
  }
</style>
