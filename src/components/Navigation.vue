<template>
    <!-- NAVIGATION -->
    <nav>
      <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
      <router-link to="/about"><i class="fa fa-user"></i> About Me</router-link>
      <router-link to="/resume"><i class="fa fa-file"></i> My Resume</router-link>
      <router-link to="/site"><i class="fa fa-code"></i> This Site</router-link>
    </nav>
</template>

<style lang="less" scoped>
@import url("../assets/styles/variables.less");

nav {
    padding: @basePadding 0;
    background-color: darken(@background-color,20%);
    display: flex;
    justify-content: space-evenly;
    width: 100vw;
    position: sticky;
    top: 0;
    box-shadow: 0 0 8px @gray75;

    a {
      color: @gray25;
      text-decoration: none;
      padding: 5px 3px 3px;
      margin-left: 8px;
      border-bottom: 1px dotted darken(@background-color,20%);
      border-top: 1px dotted darken(@background-color,20%);

      &:hover {
        color: @gray10;
        border-bottom: 1px dotted @primary-color;
      }

      &.router-link-exact-active {
        color: @white;
        border-bottom: 1px dotted @white;
        border-top: 1px dotted @white;
      }
    }

    .fa {
      margin-right: 8px;
    }
  }
</style>