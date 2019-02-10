<template>
    <!-- NAVIGATION -->
    <nav>
      <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
      <router-link to="/about"><i class="fa fa-user"></i> About Me</router-link>
      <router-link to="/resume"><i class="fa fa-file"></i> My Resume</router-link>
      <router-link to="/site"><i class="fa fa-code"></i> This Site</router-link>
      <!-- <router-link to="/alphabet">The Alphabet Story</router-link> -->
      <!-- <router-link to="/projects">My Projects</router-link> -->
    </nav>
</template>

<style lang="less" scoped>
@import url("../assets/styles/variables.less");

nav {
    padding: @basePadding 0;
    background-color: #2c3e50;
    display: flex;
    justify-content: space-evenly;
    width: 100vw;
    position: sticky;
    top: 0;

    a {
      color: @gray25;
      text-decoration: none;
      padding: 4px 3px 3px;

      &:hover {
        color: @gray10;
        border-bottom: 1px dotted @primary-color;
      }

      &.router-link-exact-active {
        color: #fff;
        border-bottom: 1px dotted #fff;
        border-top: 1px dotted #fff;
      }
    }
  }
</style>

