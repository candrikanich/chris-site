<template>
  <div id="app" class="grid-container">

    <!-- NAVIGATION -->
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About Me</router-link>
      <router-link to="/resume">My Resume</router-link>
      <router-link to="/alphabet">The Alphabet Story</router-link>
      <router-link to="/projects">My Projects</router-link>
    </nav>

    <!-- CONTENT INJECTION -->
    <router-view/>
  </div>
</template>

<style lang="less">
  @import url("assets/styles/main.less");

  html {
    height: 100%;

    body {
      min-height: 100%;
    }
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
  }
  nav {
    padding: 30px;
    background-color: #ccc;

    a {
      color: #2c3e50;
      text-decoration: none;
      border-right: 1px solid green;
      margin-right: 15px;
      padding-right: 15px;

      &.router-link-exact-active {
        color: #42b983;
        font-weight: bold;
        text-decoration-color: #2c3e50;
      }

      &:last-child {
        border-right: none;
      }
    }

  }
</style>
