<template>
    <section class="landingPage">
        <header>
            <h1>Hi, I'm Chris.</h1>
            <h2>Nice to meet you. </h2>
        </header>
    </section>
    
</template>

<script>
    export default {
        name: 'landing-page',
        data() {
            return {
                pageName: 'landingPage'
            }
        }
    }
</script>

<style lang="less" scoped>
    @import url("../assets/styles/main.less");

    section.landingPage {
        background: url("../assets/img/cwa.png") center center no-repeat;
        background-attachment: fixed;
        background-size: cover;
        background-color: @background-color;
        height: 100vh;
        width: 100vw;

        header {
            padding: 1em;

            h1 {
                font-size: 3.0em;
                font-weight: bold;
            }

            h2 {
                font-size: 1.8em;
                font-weight: normal;
            }

            h1, h2 {
                padding: 0;
                margin: 0;
                line-height: 1.0em;
                text-shadow: 0 0 3px #464646;
                color: #fff;
            }
        }
        article {
            padding-top: 30%;
            background-color: #464646;
            opacity: 0.5;
        }

    }

    nav {
    background-color: rgba(255,255,255,0.5);
    z-index: 2;
    position: absolute;
    bottom: 25%;

    a {
      padding: 8px 15px;
      border: 1px solid #2c3e50;
      border-radius: 5px;
      background-color: #fff;
      font-size: @baseFontSize;

      &.router-link-exact-active {
        color: #42b983;
        font-weight: bold;
        text-decoration-color: #2c3e50;
        display: none;
      }

      &:hover {
          background-color: #2c3e50;
          color: #fff;
          border: 1px solid #000;
      }

    }

  }
</style>

