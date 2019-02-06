<template>
    <!-- NAVIGATION -->
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About Me</router-link>
      <router-link to="/resume">My Resume</router-link>
      <!-- <router-link to="/alphabet">The Alphabet Story</router-link> -->
      <!-- <router-link to="/projects">My Projects</router-link> -->
    </nav>
</template>

<style lang="less" scoped>
@import url("../assets/styles/variables.less");

nav {
    padding: @basePadding 0;
    background-color: @background-color;
    display: flex;
    justify-content: space-evenly;
    width: 100vw;
    position: sticky;
    top: 0;

    a {
      color: #2c3e50;
      text-decoration: none;
      padding: 4px 3px 3px;

      &.router-link-exact-active {
        color: #fff;
        border-bottom: 1px dotted #fff;
        border-top: 1px dotted #fff;
      }
    }
  }
</style>

