<template>
  <div id="app" class="grid-container">

    <!-- NAVIGATION -->
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About Me</router-link>
      <router-link to="/resume">My Resume</router-link>
      <!-- <router-link to="/alphabet">The Alphabet Story</router-link> -->
      <!-- <router-link to="/projects">My Projects</router-link> -->
    </nav>

    <!-- CONTENT INJECTION -->
    <router-view/>
  </div>
</template>

<style lang="less">
  @import url("assets/styles/main.less");

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }
  nav {
    padding: @basePadding 0;
    background-color: @background-color;
    display: flex;
    justify-content: space-evenly;
    width: 100vw;
    height: 1fr;

    a {
      color: #2c3e50;
      text-decoration: none;


      &.router-link-exact-active {
        color: #fff;
        font-weight: bold;
        // text-decoration: underline overline dotted #fff;
        border-bottom: 1px dotted #fff;
        border-top: 1px dotted #fff;
      }
    }

  }
</style>
